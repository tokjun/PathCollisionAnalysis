cmake_minimum_required(VERSION 2.8.9)

project(PathCollisionAnalysis)

#-----------------------------------------------------------------------------
# Extension meta-information
set(EXTENSION_HOMEPAGE "http://slicer.org/slicerWiki/index.php/Documentation/Nightly/Extensions/PathCollisionAnalysis")
set(EXTENSION_CATEGORY "Informatics")
set(EXTENSION_CONTRIBUTORS "John Doe (AnyWare Corp.)")
set(EXTENSION_DESCRIPTION "This is an example of a simple extension")
set(EXTENSION_ICONURL "http://www.example.com/Slicer/Extensions/PathCollisionAnalysis.png")
set(EXTENSION_SCREENSHOTURLS "http://www.example.com/Slicer/Extensions/PathCollisionAnalysis/Screenshots/1.png")

#-----------------------------------------------------------------------------
# Extension dependencies
find_package(Slicer REQUIRED)
include(${Slicer_USE_FILE})

#-----------------------------------------------------------------------------
# Extension modules
add_subdirectory(PathCollisionAnalysis)
## NEXT_MODULE

#-----------------------------------------------------------------------------
include(${Slicer_EXTENSION_CPACK})
