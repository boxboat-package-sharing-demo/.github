# Dotnet Packages Demo 👀

This repository tries to showcase how:
- to publish a package from a repository
- to consume a package from another repository
- to share actions from a single repository
- to ensure that a self-hosted runner is able to authenticate against GitHub packages

## 🍔 The Consumer

The application that consumes GitHub Packages from this organization

## 🏭 The Producer

The source repository that publishes a NuGet package

## ⚙️ The Shared Workflows

The composite github action used to clean and restore a build.


