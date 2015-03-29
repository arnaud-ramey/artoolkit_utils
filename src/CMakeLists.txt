ADD_EXECUTABLE( artoolkit_img2patt artoolkit_img2patt.cpp)
ADD_EXECUTABLE( artoolkit_patt2img artoolkit_patt2img.cpp)
TARGET_LINK_LIBRARIES( artoolkit_img2patt ${OpenCV_LIBS} ${Boost_LIBRARIES})
TARGET_LINK_LIBRARIES( artoolkit_patt2img ${OpenCV_LIBS} ${Boost_LIBRARIES})


