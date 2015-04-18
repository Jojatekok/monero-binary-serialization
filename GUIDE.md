_**NOTE:** This guide is not yet finished._

## Introduction

Monero core applications use serialization methods to make communication with other software easier.
One of those serialization formats is binary, and it is way less specific and documented than JSON.

## The basics of binary serialization

BLOBs _(Binary Large OBjects)_ are used to store any kind of digital data. While they are extremely flexible, defining standards is a must whenever developers utilize them. In the case of Monero's C++ assemblies, macros are used to make serialization straightforward for coders, and formal for end-users.
