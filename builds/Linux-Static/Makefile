# Automatically generated makefile, created by the Introjucer
# Don't edit this file! Your changes will be overwritten when you re-save the Introjucer project!

# (this disables dependency generation if multiple architectures are set)
DEPFLAGS := $(if $(word 2, $(TARGET_ARCH)), , -MMD)

ifndef CONFIG
  CONFIG=Debug
endif

ifeq ($(CONFIG),Debug)
  BINDIR := build
  LIBDIR := build
  OBJDIR := build/intermediate/Debug
  OUTDIR := build

  ifeq ($(TARGET_ARCH),)
    TARGET_ARCH := -march=native
  endif

  CPPFLAGS := $(DEPFLAGS) -D "LINUX=1" -D "DEBUG=1" -D "_DEBUG=1" -D "JUCE_PLUGINHOST_AU" -D "__SEPARATION_FLOAT_PRECISION__" -D "__UNIX__" -D "JUCER_LINUX_MAKE_E75DDA05=1" -I /usr/include -I /usr/include/freetype2 -I ../../../JuceLibraryCode
  CFLAGS += $(CPPFLAGS) $(TARGET_ARCH) -g -ggdb -O0 -msse -msse2 -std=c++0x -fopenmp -I../../../sdks/eigen/
  CXXFLAGS += $(CFLAGS)
  LDFLAGS += $(TARGET_ARCH) -L$(BINDIR) -L$(LIBDIR) -lpthread -lgomp /usr/lib64/libfftw3f.a
  LDDEPS :=
  RESFLAGS :=  -D "LINUX=1" -D "DEBUG=1" -D "_DEBUG=1" -D "JUCE_PLUGINHOST_AU" -D "__SEPARATION_FLOAT_PRECISION__" -D "__UNIX__" -D "JUCER_LINUX_MAKE_E75DDA05=1" -I /usr/include -I /usr/include/freetype2 -I ../../../JuceLibraryCode
  TARGET := ISSE
  BLDCMD = $(CXX) -o $(OUTDIR)/$(TARGET) $(OBJECTS) $(LDFLAGS) $(RESOURCES) $(TARGET_ARCH)
endif

ifeq ($(CONFIG),Release)
  BINDIR := build
  LIBDIR := build
  OBJDIR := build/intermediate/Release
  OUTDIR := build

  ifeq ($(TARGET_ARCH),)
    TARGET_ARCH := -march=native
  endif

  CPPFLAGS := $(DEPFLAGS) -D "LINUX=1" -D "NDEBUG=1" -D "JUCE_PLUGINHOST_AU" -D "__SEPARATION_FLOAT_PRECISION__" -D "__UNIX__" -D "JUCER_LINUX_MAKE_E75DDA05=1" -I /usr/include -I /usr/include/freetype2 -I ../../../JuceLibraryCode
  CFLAGS += $(CPPFLAGS) $(TARGET_ARCH) -O3 -msse -msse2 -std=c++0x -fopenmp -I../../../sdks/eigen/
  CXXFLAGS += $(CFLAGS)
  LDFLAGS += $(TARGET_ARCH) -L$(BINDIR) -L$(LIBDIR) -fvisibility=hidden -lpthread -lgomp /usr/lib64/libfftw3f.a
  LDDEPS :=
  RESFLAGS :=  -D "LINUX=1" -D "NDEBUG=1" -D "JUCE_PLUGINHOST_AU" -D "__SEPARATION_FLOAT_PRECISION__" -D "__UNIX__" -D "JUCER_LINUX_MAKE_E75DDA05=1" -I /usr/include -I /usr/include/freetype2 -I ../../../JuceLibraryCode
  TARGET := ISSE
  BLDCMD = $(CXX) -o $(OUTDIR)/$(TARGET) $(OBJECTS) $(LDFLAGS) $(RESOURCES) $(TARGET_ARCH)
endif

OBJECTS := \
  $(OBJDIR)/SeparationEngine_bf170f17.o \
  $(OBJDIR)/ISSEngine_8e066531.o \
  $(OBJDIR)/PluginComponent_dd618245.o \
  $(OBJDIR)/AudioFormatReaderLoopSource_906664a.o \
  $(OBJDIR)/AudioSink_971023c4.o \
  $(OBJDIR)/AudioSource_31139a4c.o \
  $(OBJDIR)/EnergyEnvelope_57fdcee7.o \
  $(OBJDIR)/PluginThread_c37f738c.o \
  $(OBJDIR)/ISSFft_cfc6256f.o \
  $(OBJDIR)/ISSStft_3fe359de.o \
  $(OBJDIR)/VirtualTestUser_d0891fe3.o \
  $(OBJDIR)/VirtualUser_b2eee9b1.o \
  $(OBJDIR)/FilterGraph_6d5a5609.o \
  $(OBJDIR)/GraphEditorPanel_185699c0.o \
  $(OBJDIR)/MainHostWindow_ccd97628.o \
  $(OBJDIR)/PluginListWindow_e832e118.o \
  $(OBJDIR)/FilePlayerProcessor_7b6af450.o \
  $(OBJDIR)/Layer_45a8b48c.o \
  $(OBJDIR)/ImageLayer_c72ab25.o \
  $(OBJDIR)/VizRenderThread_298e51c2.o \
  $(OBJDIR)/MaskLayer_75ace400.o \
  $(OBJDIR)/TrainingSelectionAction_8df088e3.o \
  $(OBJDIR)/AddToMaskAction_f0304199.o \
  $(OBJDIR)/ClearMaskAction_82b8772a.o \
  $(OBJDIR)/BoxBrushImgAction_f5360a25.o \
  $(OBJDIR)/ClearImageAction_397e6d3.o \
  $(OBJDIR)/PaintBrushImgAction_2d9d3c78.o \
  $(OBJDIR)/ColorMap_f1f9fa68.o \
  $(OBJDIR)/SpectrogramSettings_745e33eb.o \
  $(OBJDIR)/Timeline_90824bb0.o \
  $(OBJDIR)/TransportComp_540a3b93.o \
  $(OBJDIR)/MainToolbar_9cf8edbd.o \
  $(OBJDIR)/ToolbarProgress_cdf04303.o \
  $(OBJDIR)/BrushPanel_43f8b59.o \
  $(OBJDIR)/AboutPage_d8602a77.o \
  $(OBJDIR)/ImgBinaryData_aca58629.o \
  $(OBJDIR)/ImgToolbarButton_76833479.o \
  $(OBJDIR)/ToolbarItemFact_e70e3bf5.o \
  $(OBJDIR)/ToolbarSlider_2b2033f7.o \
  $(OBJDIR)/AppCommandIDs_7e8d6749.o \
  $(OBJDIR)/Main_db96ae28.o \
  $(OBJDIR)/DocWindow_e7649c03.o \
  $(OBJDIR)/TimelineView_105d1a75.o \
  $(OBJDIR)/MainContentComp_18c6e86a.o \
  $(OBJDIR)/Track_d45e4386.o \
  $(OBJDIR)/MultiTrack_4c1c8801.o \
  $(OBJDIR)/MultiPaintView_e0cc0a59.o \
  $(OBJDIR)/ProgramSettings_675e9f82.o \
  $(OBJDIR)/ThreadHelpers_eb26f556.o \
  $(OBJDIR)/ToolbarState_82deb5c5.o \
  $(OBJDIR)/NewProjectMenu_83139ac7.o \
  $(OBJDIR)/ISSLogger_1ae0c3b4.o \
  $(OBJDIR)/BinaryData_51699c3.o \

.PHONY: clean

$(OUTDIR)/$(TARGET): $(OBJECTS) $(LDDEPS) $(RESOURCES)
	@echo Linking ISSE
	-@mkdir -p $(BINDIR)
	-@mkdir -p $(LIBDIR)
	-@mkdir -p $(OUTDIR)
	@$(BLDCMD)

clean:
	@echo Cleaning ISSE
	-@rm -f $(OUTDIR)/$(TARGET)
	-@rm -rf $(OBJDIR)/*
	-@rm -rf $(OBJDIR)

strip:
	@echo Stripping ISSE
	-@strip --strip-unneeded $(OUTDIR)/$(TARGET)

$(OBJDIR)/SeparationEngine_bf170f17.o: ../../../src/SeparationEngine.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling SeparationEngine.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ISSEngine_8e066531.o: ../../../src/api/ISSEngine.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ISSEngine.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/PluginComponent_dd618245.o: ../../../src/PluginComponent.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling PluginComponent.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/AudioFormatReaderLoopSource_906664a.o: ../../../src/AudioFormatReaderLoopSource.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling AudioFormatReaderLoopSource.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/AudioSink_971023c4.o: ../../../src/AudioSink.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling AudioSink.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/AudioSource_31139a4c.o: ../../../src/AudioSource.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling AudioSource.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/EnergyEnvelope_57fdcee7.o: ../../../src/EnergyEnvelope.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling EnergyEnvelope.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/PluginThread_c37f738c.o: ../../../src/PluginThread.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling PluginThread.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ISSFft_cfc6256f.o: ../../../src/api/ISSFft.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ISSFft.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ISSStft_3fe359de.o: ../../../src/api/ISSStft.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ISSStft.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/VirtualTestUser_d0891fe3.o: ../../../src/VirtualTestUser.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling VirtualTestUser.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/VirtualUser_b2eee9b1.o: ../../../src/VirtualUser.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling VirtualUser.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/FilterGraph_6d5a5609.o: ../../../src/plugin/FilterGraph.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling FilterGraph.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/GraphEditorPanel_185699c0.o: ../../../src/plugin/GraphEditorPanel.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling GraphEditorPanel.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/MainHostWindow_ccd97628.o: ../../../src/plugin/MainHostWindow.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling MainHostWindow.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/PluginListWindow_e832e118.o: ../../../src/plugin/PluginListWindow.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling PluginListWindow.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/FilePlayerProcessor_7b6af450.o: ../../../src/FilePlayerProcessor.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling FilePlayerProcessor.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/Layer_45a8b48c.o: ../../../src/Layer.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling Layer.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ImageLayer_c72ab25.o: ../../../src/ImageLayer.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ImageLayer.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/VizRenderThread_298e51c2.o: ../../../src/VizRenderThread.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling VizRenderThread.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/MaskLayer_75ace400.o: ../../../src/MaskLayer.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling MaskLayer.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/TrainingSelectionAction_8df088e3.o: ../../../src/TrainingSelectionAction.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling TrainingSelectionAction.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/AddToMaskAction_f0304199.o: ../../../src/AddToMaskAction.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling AddToMaskAction.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ClearMaskAction_82b8772a.o: ../../../src/ClearMaskAction.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ClearMaskAction.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/BoxBrushImgAction_f5360a25.o: ../../../src/BoxBrushImgAction.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling BoxBrushImgAction.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ClearImageAction_397e6d3.o: ../../../src/ClearImageAction.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ClearImageAction.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/PaintBrushImgAction_2d9d3c78.o: ../../../src/PaintBrushImgAction.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling PaintBrushImgAction.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ColorMap_f1f9fa68.o: ../../../src/ColorMap.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ColorMap.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/SpectrogramSettings_745e33eb.o: ../../../src/SpectrogramSettings.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling SpectrogramSettings.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/Timeline_90824bb0.o: ../../../src/Timeline.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling Timeline.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/TransportComp_540a3b93.o: ../../../src/TransportComp.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling TransportComp.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/MainToolbar_9cf8edbd.o: ../../../src/MainToolbar.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling MainToolbar.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ToolbarProgress_cdf04303.o: ../../../src/ToolbarProgress.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ToolbarProgress.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/BrushPanel_43f8b59.o: ../../../src/BrushPanel.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling BrushPanel.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/AboutPage_d8602a77.o: ../../../src/AboutPage.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling AboutPage.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ImgBinaryData_aca58629.o: ../../../src/ImgBinaryData.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ImgBinaryData.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ImgToolbarButton_76833479.o: ../../../src/ImgToolbarButton.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ImgToolbarButton.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ToolbarItemFact_e70e3bf5.o: ../../../src/ToolbarItemFact.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ToolbarItemFact.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ToolbarSlider_2b2033f7.o: ../../../src/ToolbarSlider.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ToolbarSlider.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/AppCommandIDs_7e8d6749.o: ../../../src/AppCommandIDs.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling AppCommandIDs.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/Main_db96ae28.o: ../../../src/Main.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling Main.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/DocWindow_e7649c03.o: ../../../src/DocWindow.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling DocWindow.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/TimelineView_105d1a75.o: ../../../src/TimelineView.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling TimelineView.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/MainContentComp_18c6e86a.o: ../../../src/MainContentComp.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling MainContentComp.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/Track_d45e4386.o: ../../../src/Track.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling Track.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/MultiTrack_4c1c8801.o: ../../../src/MultiTrack.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling MultiTrack.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/MultiPaintView_e0cc0a59.o: ../../../src/MultiPaintView.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling MultiPaintView.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ProgramSettings_675e9f82.o: ../../../src/ProgramSettings.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ProgramSettings.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ThreadHelpers_eb26f556.o: ../../../src/ThreadHelpers.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ThreadHelpers.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ToolbarState_82deb5c5.o: ../../../src/ToolbarState.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ToolbarState.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/NewProjectMenu_83139ac7.o: ../../../src/NewProjectMenu.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling NewProjectMenu.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/ISSLogger_1ae0c3b4.o: ../../../src/ISSLogger.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling ISSLogger.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

$(OBJDIR)/BinaryData_51699c3.o: ../../../JuceLibraryCode/BinaryData.cpp
	-@mkdir -p $(OBJDIR)
	@echo "Compiling BinaryData.cpp"
	@$(CXX) $(CXXFLAGS) -o "$@" -c "$<"

-include $(OBJECTS:%.o=%.d)
