# RandomNameGeneratorHub

Hub for my Random Name Generator libraries written in various languages.

This started as me wanting to wrap with Gradle a Java class library that
I thought was cool. Later on, I started using it as a kind of personal
kata when I started working on a programming language for the first
tiem. 

## Repositories

* Ruby:
  [random_name_generator](https://github.com/folkengine/random_name_generator)

This is the version that has gotten the most traction, including a
contribution of Russian language versions of some of the dialects. I'm
proud of this version of the framework. It's my first complete rewrite
of the original Java code I found online and I consider it solid.

* Rust:
  [random_name_generator_rs](https://github.com/folkengine/random_name_generator_rs)

This is a port of the Ruby version that I like a lot. Rust is my happy
place language right now, and this was a great way to get into the
language.

* Java:
  [java-random-name-generator](https://github.com/folkengine/java-random-name-generator)

For this version, I just wanted to take Sinipull's code on
[codecall,net](http://forum.codecall.net/topic/49665-java-random-name-generator/)
and add Gradle to is so that it could be easily included in other project.

It would be fun to completely refactor this code, adding test coverage,
etc.

* Go: [goname](https://github.com/folkengine/goname)

(**needs refactoring**)

TBH, I don't trust this randomization of this version, and makes me
think that I need to explore ways to create a consistent testing
strategy for every version of the library.

I wrote it before go modules came along, so it's in desperate need of an
overhaul.

## Extended Testing Strategies

A big part of making the testing of the versions consistend will be from
adding the ability to do seeded randomization for each. While RSpec
makes this easy in Ruby, it's a bigger challenge in other languages from
what I can tell.

## TODO

Some of these I want to do as a way to get a feel for the nuances of
working between languages in the same femily, such as
JavaScript/TypeScript, Erlang/Elixir, and C#/F#.

* JavaScript
* TypeScript
* Elixir
* Erlang
* C#
* F#
* Scala
* Clojure
* Java 15

### Tolkien Mode

One of the crazier ideas that I would love to get going is what I call
Tolkien Mode. One of the things that I always thought was really cool
about the languages that Tolkien created in LOTR is that there are
multiple scripts for the languages he invented. How totally bad assed
would it be for the library to be able to print out randomly generated
Elvish names in Tengwar or Cirth?

I did some preliminary investigation to see what was out there for
fonts, and quickly gave up given how daunting is seemed.
