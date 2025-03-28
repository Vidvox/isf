# Interactive Shader Format

ISF stands for "Interactive Shader Format", and is a file format that describes a GLSL fragment shader, as well as how to execute and interact with it. The goal of this file format is to provide a simple and minimal interface for image filters and generative video sources that allows them to be interacted with and reused in a generic and modular fashion.

More information can be found on the official [ISF website](https://isf.video).

ISF was originally created by [VIDVOX](https://vidvox.net) in 2013 and is now on version 2.0 of its release.

## ISF Specification

The [ISF Specification Page](https://github.com/mrRay/ISF_Spec/) contains detailed information about ISF application developers, along with links to source code repositories and other useful resources to get started with.

## Supported Software

The [ISF Integrations](https://isf.video/integrations/) page contains a list of applications that support ISF.

## ISF Documentation

Information related to using ISF compositions and FX in various host software can be found here: [ISF Documentation](https://docs.isf.video).

This includes:
- The ISF Quick Start, a guide to quickly get started with writing GLSL shaders in the ISF specification. A good starting point for people who already know how to code and are just looking to understand the core concepts of ISF.
- The ISF Reference Pages, an overview of the available built-in variables, functions and other conventions used by ISF as a quick reference for shader developers.
- The ISF Primer, a set of in depth lessons with walkthroughs for writing your first GLSL shaders and discussion of advanced usages of the ISF specification.

## ISF Shader Library

The standard set of ISF compositions and FX that are included with VDMX can be found here: [ISF Files](https://github.com/Vidvox/ISF-Files)

Simple test ISF files that demonstrate ISF's basic features: [ISF Test/Tutorial filters](http://vidvox.net/rays_oddsnends/ISF%20tests+tutorials.zip)
(these are test filters, and we don't expect them to have signifcant creative use)

A community website where ISF files can be created, viewed and shared online can be found here: [editor.isf.video](https://editor.isf.video)

## Developer Frameworks

These existing libraries and frameworks can be used to add support for ISF to applications on desktop, mobile and the web.

- Objective-C & Metal: [ISFMSLKit](https://github.com/mrRay/ISFMSLKit) (macOS)
- Objective-C & OpenGL: [vvopensource](https://github.com/mrRay/vvopensource) (macOS / iOS)
- C++ & OpenGL: [vvisf-gl](https://github.com/mrRay/vvisf-gl) (macOS / iOS/ Win / Linux)
- Javascript & WebGL: [ISF-JS](https://github.com/msfeldstein/interactive-shader-format-js) (Web)

Additional libraries can be found on the [ISF Developers](https://isf.video/developers/) page.
