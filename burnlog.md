# Kubernetes burn log

_for whatever your team name was ...

no seariously, you guys didn't tell me
once in the 2wks what ya'll actually do..._


### Upcoming


#### General
  - controller and old etcd portions don't play notice
  - roles an don't play nice we will be using roles from here on out so there
    is a migration path for that.
      - AWS service key interaction smust be define, quaranteened and removced
      - role based deployments will need to have their fact interpretted for them (facts aren't collect appropriaterly withjpout tying in the a was sdk)
      - Makefile will need to be reintroduced....
      - there's something else but seriously.... i slept im 20hrs... #trollcommit
  - Oh yeah, their on bleed edge because their running EKS over AWS... wtlfc

#### Terraform
 - sgtruct
 - module
 - displace vpc from whatever...
 = train my guy to do this... rufkn serious?

#### Ansible
 - Roles need to be consolidated
   - etcd needs to migrated back into the controller (+1.4) not longort a quarum,
     of etcd clusters.
 - rehab all those stupid ansible portions based on facts, the old shit is not
   compatible with thcirca 2007 shit and it needs to have a commonality that is
    cross versiojn at least until 1.11.x, after that it's your prob, dont care 



### In Proc

....

### Closed

....