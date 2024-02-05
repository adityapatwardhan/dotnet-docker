**IMPORTANT**

**The images from the dotnet/nightly repositories include last-known-good (LKG) builds for the next release of [.NET](https://github.com/dotnet/core).**

**See [dotnet](https://hub.docker.com/_/microsoft-dotnet-aspire-dashboard/) for images with official releases of [.NET](https://github.com/dotnet/core).**

# Featured Tags

* `8.0-preview` (Preview)
  * `docker pull mcr.microsoft.com/dotnet/nightly/aspire-dashboard:8.0-preview`

# About

This image contains the .NET Aspire Dashboard.

Watch [discussions](https://github.com/dotnet/dotnet-docker/discussions/categories/announcements) for Docker-related .NET announcements.

# Usage

The [.NET Docker samples](https://github.com/dotnet/dotnet-docker/blob/main/samples/README.md) show various ways to use .NET and Docker together. See [Building Docker Images for .NET Applications](https://docs.microsoft.com/dotnet/core/docker/building-net-docker-images) to learn more.



# Image Variants

.NET container images have several variants that offer different combinations of flexibility and deployment size.
The [Image Variants documentation](https://github.com/dotnet/dotnet-docker/blob/main/documentation/image-variants.md) contains a summary of the image variants and their use-cases.

# Related Repositories

.NET:

* [dotnet](https://hub.docker.com/_/microsoft-dotnet/): .NET
* [dotnet/samples](https://hub.docker.com/_/microsoft-dotnet-samples/): .NET Samples
* [dotnet/nightly/sdk](https://hub.docker.com/_/microsoft-dotnet-nightly-sdk/): .NET SDK (Preview)
* [dotnet/nightly/aspnet](https://hub.docker.com/_/microsoft-dotnet-nightly-aspnet/): ASP.NET Core Runtime (Preview)
* [dotnet/nightly/runtime](https://hub.docker.com/_/microsoft-dotnet-nightly-runtime/): .NET Runtime (Preview)
* [dotnet/nightly/runtime-deps](https://hub.docker.com/_/microsoft-dotnet-nightly-runtime-deps/): .NET Runtime Dependencies (Preview)
* [dotnet/nightly/monitor](https://hub.docker.com/_/microsoft-dotnet-nightly-monitor/): .NET Monitor Tool (Preview)

.NET Framework:

* [dotnet/framework](https://hub.docker.com/_/microsoft-dotnet-framework/): .NET Framework, ASP.NET and WCF
* [dotnet/framework/samples](https://hub.docker.com/_/microsoft-dotnet-framework-samples/): .NET Framework, ASP.NET and WCF Samples

# Full Tag Listing

## Linux amd64 Tags
##### .NET Aspire Dashboard Preview Tags
Tags | Dockerfile | OS Version
-----------| -------------| -------------
8.0.0-preview.3-cbl-mariner-distroless-amd64, 8.0-preview-cbl-mariner-distroless-amd64, 8.0.0-preview.3-cbl-mariner-distroless, 8.0-preview-cbl-mariner-distroless, 8.0.0-preview.3, 8.0-preview | [Dockerfile](https://github.com/dotnet/dotnet-docker/blob/nightly/src/aspire-dashboard/8.0/cbl-mariner-distroless/amd64/Dockerfile) | CBL-Mariner 2.0-distroless

## Linux arm64 Tags
##### .NET Aspire Dashboard Preview Tags
Tags | Dockerfile | OS Version
-----------| -------------| -------------
8.0.0-preview.3-cbl-mariner-distroless-arm64v8, 8.0-preview-cbl-mariner-distroless-arm64v8, 8.0.0-preview.3-cbl-mariner-distroless, 8.0-preview-cbl-mariner-distroless, 8.0.0-preview.3, 8.0-preview | [Dockerfile](https://github.com/dotnet/dotnet-docker/blob/nightly/src/aspire-dashboard/8.0/cbl-mariner-distroless/arm64v8/Dockerfile) | CBL-Mariner 2.0-distroless

You can retrieve a list of all available tags for dotnet/nightly/aspire-dashboard at https://mcr.microsoft.com/v2/dotnet/nightly/aspire-dashboard/tags/list.
<!--End of generated tags-->

For tags contained in the old dotnet/core-nightly/aspire-dashboard repository, you can retrieve a list of those tags at https://mcr.microsoft.com/v2/dotnet/core-nightly/aspire-dashboard/tags/list.

*Tags not listed in the table above are not supported. See the [Supported Tags Policy](https://github.com/dotnet/dotnet-docker/blob/main/documentation/supported-tags.md)*

# Support

## Lifecycle

* [Microsoft Support for .NET](https://github.com/dotnet/core/blob/main/support.md)
* [Supported Container Platforms Policy](https://github.com/dotnet/dotnet-docker/blob/main/documentation/supported-platforms.md)
* [Supported Tags Policy](https://github.com/dotnet/dotnet-docker/blob/main/documentation/supported-tags.md)

## Image Update Policy

* We update the supported .NET images within 12 hours of any updates to their base images (e.g. debian:buster-slim, windows/nanoserver:ltsc2022, buildpack-deps:bionic-scm, etc.).
* We publish .NET images as part of releasing new versions of .NET including major/minor and servicing.

## Feedback

* [File an issue](https://github.com/dotnet/dotnet-docker/issues/new/choose)
* [Contact Microsoft Support](https://support.microsoft.com/contactus/)

# License

* Legal Notice: [Container License Information](https://aka.ms/mcr/osslegalnotice)
* [.NET license](https://github.com/dotnet/dotnet-docker/blob/main/LICENSE)
* [Discover licensing for Linux image contents](https://github.com/dotnet/dotnet-docker/blob/main/documentation/image-artifact-details.md)
* [Windows base image license](https://docs.microsoft.com/virtualization/windowscontainers/images-eula) (only applies to Windows containers)
* [Pricing and licensing for Windows Server 2019](https://www.microsoft.com/cloud-platform/windows-server-pricing)