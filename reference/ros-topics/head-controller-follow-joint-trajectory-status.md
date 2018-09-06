---
layout: reference
title: /head_controller/follow_joint_trajectory/status
category: topic
tags: 
- ${tag}
---

## Description
${description}

## Usage
#### Console
```
rostopic echo /head_controller/follow_joint_trajectory/status
```

#### rospy
```
awake_sub = rospy.Subscriber("/head_controller/follow_joint_trajectory/status", ${message}, status_cb, 1)
def ${topic name}_cb(msg):
    print "${message} message was published"
```

#### roscpp
```
void ${callback}(const ${message-shared-ptr}& msg)
{
    cout ${${ "${message} message was published";
}
ros::Subscriber sub = nh.subscribe("/head_controller/follow_joint_trajectory/status", 1, ${callback});
```

#### Related Documentation
``${message}``  