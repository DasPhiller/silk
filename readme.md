# FabrikMC

FabrikMC is an API for using FabricMC with Kotlin

It offers:
- an Inventory GUI API
- a Kotlin wrapper for Brigardier
- a Kotlin DSL for creating complex Text objects
- Coroutine Utilities
- kotlinx.serialization Support
- a scoreboard (sideboard) API

This is not Fabric, this is just a Kotlin extension for Fabric - called Fabri<ins>k</ins>.

Fabrik does not put a whole new API on top of Mojang's code, instead it provides utilities which make high use of the possibilites Kotlin gives you. You decide where to use Fabrik, Fabric or just the Vanilla Code. Additionally, Fabrik is structured in modules, meaning that you can just take what you need.

## Dependency

The core module:

Gradle _Kotlin DSL_
```kotlin
implementation("net.axay:fabrikmc-core:version")
```

Gradle _Groovy DSL_
```groovy
implementation 'net.axay:fabrikmc-core:version'
```

You can find all **available modules**, and the **current version**, on [Maven Central](https://repo1.maven.org/maven2/net/axay/).
