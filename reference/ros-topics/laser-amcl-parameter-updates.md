---
layout: reference
title: /laser_amcl/parameter_updates
category: topic
tags: 
- ${tag}
---

## Description
${description}

## Usage
#### Console
```
rostopic echo /laser_amcl/parameter_updates
```

#### rospy
```
awake_sub = rospy.Subscriber("/laser_amcl/parameter_updates", ${message}, parameter_updates_cb, 1)
def ${topic name}_cb(msg):
    print "${message} message was published"
```

#### roscpp
```
void ${callback}(const ${message-shared-ptr}& msg)
{
    cout ${${ "${message} message was published";
}
ros::Subscriber sub = nh.subscribe("/laser_amcl/parameter_updates", 1, ${callback});
```

#### Related Documentation
``${message}``  