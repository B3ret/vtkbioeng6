ADD_EXECUTABLE(TestCollisionDetection TestCollisionDetection.cxx)
ADD_EXECUTABLE(TestCollisionDetection1 TestCollisionDetection1.cxx)

TARGET_LINK_LIBRARIES(TestCollisionDetection ${VTK_LIBRARIES} vtkBioeng)
TARGET_LINK_LIBRARIES(TestCollisionDetection1 ${VTK_LIBRARIES} vtkBioeng)