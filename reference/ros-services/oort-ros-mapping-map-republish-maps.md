---
layout: reference
title: /oort_ros_mapping/map/republish_maps
category: service
tags: 
- ${tag} 
- ${tag}
---

## Description
${description}

## Usage
#### Console
```
rosservice call /oort_ros_mapping/map/republish_maps ${arguments}
```

#### rospy
```
republish_maps_srv = rospy.ServiceProxy("/oort_ros_mapping/map/republish_maps", ${message}, 1)
republish_maps_srv()
```

#### roscpp
```
ros::ServiceClient client = nh.serviceClient${message}("/oort_ros_mapping/map/republish_maps");
${message} msg;
...
if (client.call(msg))
{
    cout << "Service responded with message";
}
```

## Response
```
${paste the response from calling the service on the console}
```

## Related Documentation
``${message}``  