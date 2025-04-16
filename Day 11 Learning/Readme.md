AWS CFT(Cloud Formation Template)

1. Used to create Infrastructure on aws(IAC)
2. AWS CFT acts as a middle man(IAC) between user and aws cloud provider in which it asks users to sent the request in yaml or json format and then it will read that input and then convert that into aws api call.
3. Principlas of IAC
   a. Declarative in nature(What you see is what you have)
   b. Versioned in nature
4. when to use AWS CLI? - whenever we have to perform quick actions for ex:- list the s3 buckets.
5. when to use AWS CFT?- whenever we want to create new resources for ex:- create ec2 instance.
6. Supoorts both json and yaml language.
7. yaml supports commenting highy recommended to use.
8. yaml is less complex.
9. yaml uses identation and json uses brackets.
10. CFT supports a. Creating Infrastructure
                 b. Drift Detection(detect drift it will detect the changes if someone has made changes to the infra which you developed)
11. basics compenents of yaml file-
    a. Version
    b. description.
    c. Parameters
    d. Defibne rules.
    e. Mappings.
    f. conditions.
    g. Resources(Mandatory)
    h. Outputs

Download VScode plugins to write the cft templates easily
1. YAML by redhat
2. AWS Toolkit by aws

Difference between Terraform and CFT?
1. Terraform is a multi cloud providers CFT is only AWS
