# scalaz-jdbc

[![Gitter](https://badges.gitter.im/scalaz/scalaz-jdbc.svg)](https://gitter.im/scalaz/scalaz-jdbc?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Goal

A high-performance, purely-functional, low-level, and unopinionated library that wraps JDBC using ZIO.

## Introduction & Highlights

scalaz-jdbc provides a high-performance, purely-functional, type-safe low-level API that wraps JDBC using ZIO.

A library allows to write, combine and create programs that uses JDBC.

* Purely-functional interface that cleanly integrates with ZIO and Scalaz.
* Fully asynchronous implementation on top of synchronous JDBC.
* Composable API

## Competition

| | Slick | Doobie | Quill | JDBC |
---|---|---|---|---
Purely-functional| partial | ✓ | 𐄂 | 𐄂 |
Asynchronous| ✓ | ✓ | ✓ | 𐄂 |
High-performance| ✓ | ✓ | ✓ | ✓ |
Scalaz Integration| 𐄂 | ✓ | 𐄂 | 𐄂 |

## Background

* <a href = "https://www.youtube.com/watch?v=M5MF6M7FHPo"> SBTB 2015: Rob Norris, Programs as Values: JDBC Programming with Doobie </a>
* <a href= "https://www.youtube.com/watch?v=nqSYccoSeio"> Scylla, Charybdis, and the mystery of Quill by Flavio Brasil"> </a>
* <a href= "https://softwaremill.com/comparing-scala-relational-database-access-libraries/"> https://softwaremill.com/comparing-scala-relational-database-access-libraries/ </a>
