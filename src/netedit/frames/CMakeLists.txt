set(netedit_frames_SRCS
   GNEFrame.h
   GNEFrame.cpp
   GNEInspectorFrame.h
   GNEInspectorFrame.cpp
   GNESelectorFrame.h
   GNESelectorFrame.cpp
   GNEConnectorFrame.h
   GNEConnectorFrame.cpp
   GNETLSEditorFrame.h
   GNETLSEditorFrame.cpp
   GNEAdditionalFrame.h
   GNEAdditionalFrame.cpp
   GNECrossingFrame.h
   GNECrossingFrame.cpp
   GNETAZFrame.h
   GNETAZFrame.cpp
   GNEDeleteFrame.h
   GNEDeleteFrame.cpp
   GNEPolygonFrame.h
   GNEPolygonFrame.cpp
   GNECreateEdgeFrame.h
   GNECreateEdgeFrame.cpp
   GNERouteFrame.h
   GNERouteFrame.cpp
   GNEStopFrame.h
   GNEStopFrame.cpp
   GNEVehicleFrame.h
   GNEVehicleFrame.cpp
   GNEVehicleTypeFrame.h
   GNEVehicleTypeFrame.cpp
   GNEProhibitionFrame.h
   GNEProhibitionFrame.cpp
   )

add_library(netedit_frames STATIC ${netedit_frames_SRCS})
set_property(TARGET netedit_frames PROPERTY PROJECT_LABEL "z_netedit_frames")