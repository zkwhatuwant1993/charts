# Zookeeper Helm Chart

## prerequisites

### System Requirements

Supported Platforms

ZooKeeper consists of multiple components. Some components are supported broadly, and other components are supported only on a smaller set of platforms.

- _Client_ is the Java client library, used by applications to connect to a ZooKeeper ensemble.
- _Server_ is the Java server that runs on the ZooKeeper ensemble nodes.
- _Native_ Client is a client implemented in C, similar to the Java client, used by applications to connect to a ZooKeeper ensemble.
- _Contrib_ refers to multiple optional add-on components.

The following matrix describes the level of support committed for running each component on different operating system platforms.

Support Matrix

| Operating System | Client                     | Server                     | Native Client              | Contrib                    |
| ---------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| GNU/Linux        | Development and Production | Development and Production | Development and Production | Development and Production |
| Solaris          | Development and Production | Development and Production | Not Supported              | Not Supported              |
| FreeBSD          | Development and Production | Development and Production | Not Supported              | Not Supported              |
| Windows          | Development and Production | Development and Production | Not Supported              | Not Supported              |
| Mac OS X         | Development Only           | Development Only           | Not Supported              | Not SupRequired Softwareported              |

Required Software

Java 1.7+ (JDK 7+).Three ZooKeeper servers is the minimum recommended size for an ensemble, and we also recommend that they run on separate machines.
For more information,see [the zookeeper's admin docs](http://zookeeper.apache.org/doc/current/zookeeperAdmin.html#sc_minimumConfiguration)

## Installing the Chart

## Uninstalling the Chart

## Configuration

## Testing