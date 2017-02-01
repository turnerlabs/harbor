
# Discussion notes around Harbor v2.  Goals, aspirations, must haves, etc...


## Primary Goals

- Decrease TCO
- Harden security to get ahead of ISO
- Improve developer happiness and ease of use




## Secondary Goals


- COMMUNITY: INCLUDE developers in the initiative, get their feedback
- COMMUNITY: OSS approach to the process
- Continue to provide savings through compute density
- Continue to ease app migrations by providing a stable, robust, frictionless compute platform
- Be opinionated on private registry (quay)
- Be opinionated on kube ?


---



## Decrease TCO

 - managed kubernetes
 - reduce ingress layer costs
    -- implement ALB's ?
    -- implement Backplane ?
    -- introduce HAProxy layer ?
 - Auto scaling barges ?
 - hosted etcd ?
 - Cleave off unused services
 - Docker 1.13 (factual registry) obsoletes Catalogit ?
 - Reduce cruft in the api's
 - Decrease/eliminate Turner datacenter dependencies
 - Public, authenticated API's (eliminate customs)


## Harden security

 - Surface image scanning from claire
 - Default isolation between containers via k8 1.5 network segmentation



## Developer happiness and ease of use


 - Auto scaling containers ?
 - Allow cron jobs / scheduled jobs
 - Simplify shipit models and api
 - Invest in Harbor compose, make it the clientside "face" of Harbor
 - Simplify/cleanup Harbor UI


## Other

  - Integrate per/app spend into UI, using cloudhealth and datadog



> Notes:

> - DO NOT sacrifice developer ease of use (don't take their UI away)
> - DO NOT put any barriers between Harbor and ACM/Route53
> - Is a "kube serverless" platform needed??



MICKEY:  Need a story around "why" we are doing this.  What value is Turner getting from this spend?


