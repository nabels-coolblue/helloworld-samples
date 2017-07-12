# Overview

## Purpose

This is an example application, written in F#. The purpose of the application is simple. It is to host the minimum amount of code that is required to output a simple message to the `terminal`.

The expected message is:

```
Hello World from F#!
```

## Usage

In order to run the application and get the expected output, take the following steps:

- Download the source-code
- Go into the `helloworld` directory
- Execute the following command:

```
dotnet run 
```

## Try it yourself

It is possible to create the project that is hosted in this repository using the command-line tooling of .NET Core. Try it! Do so by running the following command:

```
dotnet new console --language F# --name helloworld
```

The next step is to run the application. 

```
cd helloworld
dotnet run
```

And voila!

```
Hello World from F#!
```

## Pre-requisites

In order to run this helloworld sample, you first need the following tools.

### [.NET Core](https://github.com/dotnet/core/blob/master/release-notes/download-archives/2.0.0-preview1-download.md)

It is not necessary to use the exact version of the dotnet core command-line tooling that is referenced in this README. But it is the one that has been used to create and run the application.

The specific version on your system can be retrieved by running the following command on the terminal:

```
> dotnet --version
Command Line Tools (_2.0.0-preview2-006497_)  
```
