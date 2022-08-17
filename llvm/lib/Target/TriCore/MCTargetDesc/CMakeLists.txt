add_llvm_component_library(LLVMTriCoreDesc
  TriCoreInstPrinter.cpp
  TriCoreMCTargetDesc.cpp
  TriCoreMCAsmInfo.cpp
  TriCoreMCCodeEmitter.cpp
  TriCoreAsmBackend.cpp
  TriCoreELFObjectWriter.cpp
  
  ADD_TO_COMPONENT
  TriCore
)