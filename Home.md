![logo](https://github.com/culturegraph/metafacture-core/wiki/img/metafacture_small.png)


Metafacture is a toolkit for processing semi-structured data with a focus on library metadata. It provides a versatile set of tools for reading, writing and transforming data. Metafacture can be used as a stand-alone application via CLI or as a Java library in other applications. There is also a playground where you can test workflows.

The name Metafacture is a portmanteau of the words metadata and manufacture.

Metafacture comprises three main parts: Framework, Flux and the Transformation-Module Fix. It can be extended with modules.

__________________

## Using Metafacture via playground or CLI

While working with the playground or the command line you only need Flux and the transformation module Fix. No JAVA-Code is necessary!
Have a look at the Getting started-Page.

## Framework for JAVA-Integration/Development

If you plan to use Metafacture as a Java library or if you wish to add commands to Flux. You should get familar with the Framework.

__________________

## FLUX

Flux is a scripting language to easily build and run processing pipelines. No Java programming is necessary, just a command line. To use Flux you may download the binary distribution of Metafacture.

For more information on how to use Flux, see the Flux User Guide.

## FIX

Metafix is a domain specific language for metadata transformation based on Catmandu FIX. The FIX object performing the transformation is used as part of a processing pipeline. If you are using the Flux scripting language to build and run pipelines, use the `fix` command. If you are using Metafacture as a Java library, just create a Metamorph object and add it to your pipeline (see also the Framework User Guide).

The transformation itself is declared in a fix-object which can be a file. For more information on how to declare transformations see Metafix User Guide.

PS: There is also the transformation modul MORPH but for that have a look at the old documentation and the german cookbook by Swissbib.

## Framework

The framework includes the interfaces and abstract classes which form the foundation of the data processing pipelines. This part of Metafacture is only relevant for you if you plan to use Metafacture as a Java library or if you wish to add pipe elements to Flux.

For more information see the Framework User Guide.
