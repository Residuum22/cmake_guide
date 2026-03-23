add_library(MathFunctions STATIC)

target_sources(MathFunctions
  PRIVATE
    MathFunctions.cxx
  PUBLIC
    FILE_SET HEADERS
    FILES 
      MathFunctions.h
)
