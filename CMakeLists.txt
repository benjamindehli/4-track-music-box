# 4-track-music-box-plugin — distributable product (VST3 / AU / Standalone).
#
# A thin wrapper over dehli-musikk-sampler-engine: this file states ONLY the product
# identity. Everything else (entry point, asset embed, sample-pack install, custom
# standalone, packaging metadata) comes from dmse_add_plugin — see
# dehli-musikk-sampler-engine/cmake/DmsePlugin.cmake.

dmse_add_plugin(FourTrackMusicBox
    PRODUCT_NAME "4-track Music Box"
    PLUGIN_CODE  Mb4t
    VERSION      2.0.0
)
