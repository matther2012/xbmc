set(SOURCES AddonCallbacksAudioDSP.cpp)

set(HEADERS AddonCallbacksAudioDSP.h)

core_add_library(api1AddonCallbacks_AudioDSP)

if(ENABLE_INTERNAL_FFMPEG)
  add_dependencies(api1AddonCallbacks_AudioDSP ffmpeg)
endif()
