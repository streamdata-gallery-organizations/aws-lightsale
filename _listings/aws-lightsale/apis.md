---
name: AWS Lightsale
x-slug: aws-lightsale
description: Amazon Lightsail is the easiest way to get started with AWS for developers
  who just need virtual private servers. Lightsail includes everything you need to
  launch your project quickly - a virtual machine, SSD-based storage, data transfer,
  DNS management, and a static IP - for a low, predictable price. You manage those
  Lightsail servers through the Lightsail console or by using the API or command-line
  interface (CLI).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
x-kinRank: "10"
x-alexaRank: ""
tags: AWS Lightsale
created: "2018-05-24"
modified: "2018-05-24"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon Lightsale API Allocate Static Ip
  x-api-slug: amazon-lightsale-api
  description: Allocates a static IP address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=AllocateStaticIp
  tags: IP Addresses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionallocatestaticip-get-openapi.md
- name: Amazon Lightsale API Attach Static Ip
  x-api-slug: amazon-lightsale-api
  description: Attaches a static IP address to a specific Amazon Lightsail instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=AttachStaticIp
  tags: IP Addresses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionattachstaticip-get-openapi.md
- name: Amazon Lightsale API Close Instance Public Ports
  x-api-slug: amazon-lightsale-api
  description: Closes the public ports on a specific Amazon Lightsail instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=CloseInstancePublicPorts
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actioncloseinstancepublicports-get-openapi.md
- name: Amazon Lightsale API Create Domain
  x-api-slug: amazon-lightsale-api
  description: Creates a domain resource for the specified domain (e.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=CreateDomain
  tags: Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actioncreatedomain-get-openapi.md
- name: Amazon Lightsale API Create Domain Entry
  x-api-slug: amazon-lightsale-api
  description: |-
    Creates one of the following entry records associated with the domain: A record, CNAME
          record, TXT record, or MX record.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=CreateDomainEntry
  tags: Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actioncreatedomainentry-get-openapi.md
- name: Amazon Lightsale API Create Instances
  x-api-slug: amazon-lightsale-api
  description: |-
    Creates one or more Amazon Lightsail virtual private servers, or
            instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=CreateInstances
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actioncreateinstances-get-openapi.md
- name: Amazon Lightsale API Create Instances From Snapshot
  x-api-slug: amazon-lightsale-api
  description: |-
    Uses a specific snapshot as a blueprint for creating one or more new instances that are
          based on that identical configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=CreateInstancesFromSnapshot
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actioncreateinstancesfromsnapshot-get-openapi.md
- name: Amazon Lightsale API Create Instance Snapshot
  x-api-slug: amazon-lightsale-api
  description: |-
    Creates a snapshot of a specific virtual private server, or
            instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=CreateInstanceSnapshot
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actioncreateinstancesnapshot-get-openapi.md
- name: Amazon Lightsale API Create Key Pair
  x-api-slug: amazon-lightsale-api
  description: Creates sn SSH key pair.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=CreateKeyPair
  tags: Key Pairs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actioncreatekeypair-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actioncreatekeypair-get-openapi.md
- name: Amazon Lightsale API Delete Domain
  x-api-slug: amazon-lightsale-api
  description: Deletes the specified domain recordset and all of its domain records.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=DeleteDomain
  tags: Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiondeletedomain-get-openapi.md
- name: Amazon Lightsale API Delete Domain Entry
  x-api-slug: amazon-lightsale-api
  description: Deletes a specific domain entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=DeleteDomainEntry
  tags: Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiondeletedomainentry-get-openapi.md
- name: Amazon Lightsale API Delete Instance
  x-api-slug: amazon-lightsale-api
  description: |-
    Deletes a specific Amazon Lightsail virtual private server, or
            instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=DeleteInstance
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiondeleteinstance-get-openapi.md
- name: Amazon Lightsale API Delete Instance Snapshot
  x-api-slug: amazon-lightsale-api
  description: |-
    Deletes a specific snapshot of a virtual private server (or
            instance).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=DeleteInstanceSnapshot
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiondeleteinstancesnapshot-get-openapi.md
- name: Amazon Lightsale API Delete Key Pair
  x-api-slug: amazon-lightsale-api
  description: Deletes a specific SSH key pair.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=DeleteKeyPair
  tags: Key Pairs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiondeletekeypair-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiondeletekeypair-get-openapi.md
- name: Amazon Lightsale API Detach Static Ip
  x-api-slug: amazon-lightsale-api
  description: |-
    Detaches a static IP from the Amazon Lightsail instance to which it is
          attached.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=DetachStaticIp
  tags: IP Addresses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiondetachstaticip-get-openapi.md
- name: Amazon Lightsale API Download Default Key Pair
  x-api-slug: amazon-lightsale-api
  description: Downloads the default SSH key pair from the user's account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=DownloadDefaultKeyPair
  tags: Key Pairs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiondownloaddefaultkeypair-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiondownloaddefaultkeypair-get-openapi.md
- name: Amazon Lightsale API Get Active Names
  x-api-slug: amazon-lightsale-api
  description: Returns the names of all active (not deleted) resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetActiveNames
  tags: Names
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetactivenames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetactivenames-get-openapi.md
- name: Amazon Lightsale API Get Blueprints
  x-api-slug: amazon-lightsale-api
  description: Returns the list of available instance images, or blueprints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetBlueprints
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetblueprints-get-openapi.md
- name: Amazon Lightsale API Get Bundles
  x-api-slug: amazon-lightsale-api
  description: Returns the list of bundles that are available for purchase.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetBundles
  tags: Bundles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetbundles-get-openapi.md
- name: Amazon Lightsale API Get Domain
  x-api-slug: amazon-lightsale-api
  description: Returns information about a specific domain recordset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetDomain
  tags: Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetdomain-get-openapi.md
- name: Amazon Lightsale API Get Domains
  x-api-slug: amazon-lightsale-api
  description: Returns a list of all domains in the user's account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetDomains
  tags: Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetdomains-get-openapi.md
- name: Amazon Lightsale API Get Instance
  x-api-slug: amazon-lightsale-api
  description: |-
    Returns information about a specific Amazon Lightsail instance, which is a virtual
          private server.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetInstance
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetinstance-get-openapi.md
- name: Amazon Lightsale API Get Instance Access Details
  x-api-slug: amazon-lightsale-api
  description: |-
    Returns temporary SSH keys you can use to connect to a specific virtual private server,
          or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetInstanceAccessDetails
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetinstanceaccessdetails-get-openapi.md
- name: Amazon Lightsale API Get Instance Metric Data
  x-api-slug: amazon-lightsale-api
  description: |-
    Returns the data points for the specified Amazon Lightsail instance metric, given an
          instance name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetInstanceMetricData
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetinstancemetricdata-get-openapi.md
- name: Amazon Lightsale API Get Instance Port States
  x-api-slug: amazon-lightsale-api
  description: |-
    Returns the port states for a specific virtual private server, or
            instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetInstancePortStates
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetinstanceportstates-get-openapi.md
- name: Amazon Lightsale API Get Instances
  x-api-slug: amazon-lightsale-api
  description: |-
    Returns information about all Amazon Lightsail virtual private servers, or
            instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetInstances
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetinstances-get-openapi.md
- name: Amazon Lightsale API Get Instance Snapshot
  x-api-slug: amazon-lightsale-api
  description: Returns information about a specific instance snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetInstanceSnapshot
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetinstancesnapshot-get-openapi.md
- name: Amazon Lightsale API Get Instance Snapshots
  x-api-slug: amazon-lightsale-api
  description: Returns all instance snapshots for the user's account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetInstanceSnapshots
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetinstancesnapshots-get-openapi.md
- name: Amazon Lightsale API Get Instance State
  x-api-slug: amazon-lightsale-api
  description: Returns the state of a specific instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetInstanceState
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetinstancestate-get-openapi.md
- name: Amazon Lightsale API Get Key Pair
  x-api-slug: amazon-lightsale-api
  description: Returns information about a specific key pair.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetKeyPair
  tags: Key Pairs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetkeypair-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetkeypair-get-openapi.md
- name: Amazon Lightsale API Get Key Pairs
  x-api-slug: amazon-lightsale-api
  description: Returns information about all key pairs in the user's account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetKeyPairs
  tags: Key Pairs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetkeypairs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetkeypairs-get-openapi.md
- name: Amazon Lightsale API Get Operation
  x-api-slug: amazon-lightsale-api
  description: Returns information about a specific operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetOperation
  tags: Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetoperation-get-openapi.md
- name: Amazon Lightsale API Get Operations
  x-api-slug: amazon-lightsale-api
  description: Returns information about all operations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetOperations
  tags: Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetoperations-get-openapi.md
- name: Amazon Lightsale API Get Operations For Resource
  x-api-slug: amazon-lightsale-api
  description: Gets operations for a specific resource (e.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetOperationsForResource
  tags: Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetoperationsforresource-get-openapi.md
- name: Amazon Lightsale API Get Regions
  x-api-slug: amazon-lightsale-api
  description: Returns a list of all valid regions for Amazon Lightsail.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetRegions
  tags: Regions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetregions-get-openapi.md
- name: Amazon Lightsale API Get Static Ip
  x-api-slug: amazon-lightsale-api
  description: Returns information about a specific static IP.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetStaticIp
  tags: IP Addresses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetstaticip-get-openapi.md
- name: Amazon Lightsale API Get Static Ips
  x-api-slug: amazon-lightsale-api
  description: Returns information about all static IPs in the user's account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=GetStaticIps
  tags: IP Addresses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actiongetstaticips-get-openapi.md
- name: Amazon Lightsale API Import Key Pair
  x-api-slug: amazon-lightsale-api
  description: Imports a public SSH key from a specific key pair.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=ImportKeyPair
  tags: Key Pairs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionimportkeypair-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionimportkeypair-get-openapi.md
- name: Amazon Lightsale API Is Vpc Peered
  x-api-slug: amazon-lightsale-api
  description: Returns a Boolean value indicating whether your Lightsail VPC is peered.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=IsVpcPeered
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionisvpcpeered-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionisvpcpeered-get-openapi.md
- name: Amazon Lightsale API Open Instance Public Ports
  x-api-slug: amazon-lightsale-api
  description: Adds public ports to an Amazon Lightsail instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=OpenInstancePublicPorts
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionopeninstancepublicports-get-openapi.md
- name: Amazon Lightsale API Peer Vpc
  x-api-slug: amazon-lightsale-api
  description: Tries to peer the Lightsail VPC with the user's default VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=PeerVpc
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionpeervpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionpeervpc-get-openapi.md
- name: Amazon Lightsale API Reboot Instance
  x-api-slug: amazon-lightsale-api
  description: Restarts a specific instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=RebootInstance
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionrebootinstance-get-openapi.md
- name: Amazon Lightsale API Release Static Ip
  x-api-slug: amazon-lightsale-api
  description: Deletes a specific static IP from your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=ReleaseStaticIp
  tags: IP Addresses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionreleasestaticip-get-openapi.md
- name: Amazon Lightsale API Start Instance
  x-api-slug: amazon-lightsale-api
  description: Starts a specific Amazon Lightsail instance from a stopped state.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=StartInstance
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionstartinstance-get-openapi.md
- name: Amazon Lightsale API Stop Instance
  x-api-slug: amazon-lightsale-api
  description: Stops a specific Amazon Lightsail instance that is currently running.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=StopInstance
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionstopinstance-get-openapi.md
- name: Amazon Lightsale API Unpeer Vpc
  x-api-slug: amazon-lightsale-api
  description: Attempts to unpeer the Lightsail VPC from the user's default VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=UnpeerVpc
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionunpeervpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionunpeervpc-get-openapi.md
- name: Amazon Lightsale API Update Domain Entry
  x-api-slug: amazon-lightsale-api
  description: Updates a domain recordset after it is created.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: ://///?Action=UpdateDomainEntry
  tags: Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/actionupdatedomainentry-get-openapi.md
- name: Amazon Lightsale API
  x-api-slug: amazon-lightsale-api
  description: Amazon Lightsail is the easiest way to get started with AWS for developers
    who just need virtual private servers. Lightsail includes everything you need
    to launch your project quickly - a virtual machine, SSD-based storage, data transfer,
    DNS management, and a static IP - for a low, predictable price. You manage those
    Lightsail servers through the Lightsail console or by using the API or command-line
    interface (CLI).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: :///
  tags: AWS Lightsale
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-lightsale/master/_listings/aws-lightsale/openapi.md
x-common:
- type: x-documentation
  url: https://docs.aws.amazon.com/lightsail/2016-11-28/api-reference/Welcome.html?fid=6DDA37DF97F08F8B-23761D4A79F7B1E
- type: x-pricing
  url: https://amazonlightsail.com/pricing/
- type: x-website
  url: https://amazonlightsail.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---