#
cache/myOrgImage1.tar $(docker image list --format "{{ .Repository }}:{{ .Tag }}" | grep "myOrgImage1")
                  docker save -o ~/docker-image-cache/myOrgImage2.tar $(docker image list --format "{{ .Repository }}:{{ .Tag }}" | grep "myOrgImage2")
                  docker save -o ~/docker-image-cache/myOrgImage3.tar $(docker image list --format "{{ .Repository }}:{{ .Tag }}" | grep "myOrgImage3")
                  docker save -o ~/docker-image-cache/myOrgImage4.tar $(docker image list --format "{{ .Repository }}:{{ .Tag }}" | grep "myOrgImage4")
                  docker save -o ~/docker-image-cache/myOrgImage5.tar $(docker image list --format "{{ .Repository }}:{{ .Tag }}" | grep "myOrgImage5")# Satan
~
    "instanceUrl": "https://devdiv.visualstudio.com/",
    "template": "TFSDEVDIV",
    "projectName": "DEVDIV",
    "areaPath": "DevDiv\\NET Fundamentals\\.NET Acquisition\\Docker",
    "iterationPath": "DevDiv",
    "notificationAliases": [ "dotnetADTeam@microsoft.com" ],
    "repositoryName":"ILLUMINATI",
    "codebaseName": "dotnet-docker"