# [Error Handling](error-handling.md)
## [About Error Handling](about-error-handling.md)
### [Error Mode](error-mode.md)
### [Last-Error Code](last-error-code.md)
### [Notifying the User](notifying-the-user.md)
### [Message Tables](message-tables.md)
### [Fatal Application Exit](fatal-application-exit.md)
### [Error Message Guidelines](error-message-guidelines.md)
## [Using Error Handling](using-error-handling.md)
### [Retrieving the Last-Error Code](retrieving-the-last-error-code.md)
## [Error Handling Reference](error-handling-reference.md)
### [Error Handling Functions](error-handling-functions.md)
#### [Beep](/windows/desktop/api/WinBase/)
#### [CaptureStackBackTrace](https://msdn.microsoft.com/en-us/library/Bb204633(v=VS.85).aspx)
#### [FatalAppExit](/windows/desktop/api/WinBase/)
#### [FlashWindow](/windows/desktop/api/Winuser/nf-winuser-flashwindow)
#### [FlashWindowEx](/windows/desktop/api/Winuser/nf-winuser-flashwindowex)
#### [FormatMessage](/windows/desktop/api/WinBase/nf-winbase-formatmessage)
#### [GetErrorMode](/windows/desktop/api/WinBase/)
#### [GetLastError](/windows/desktop/api/WinBase/)
#### [GetThreadErrorMode](/windows/desktop/api/WinBase/)
#### [MessageBeep](/windows/desktop/api/WinUser/nf-winuser-messagebeep)
#### [RtlLookupFunctionEntry](/windows/desktop/api/WinNT/nf-winnt-rtllookupfunctionentry)
#### [RtlNtStatusToDosError](/windows/desktop/api/Winternl/nf-winternl-rtlntstatustodoserror)
#### [RtlNtStatusToDosErrorNoTeb](/windows/desktop/api/Winternl/)
#### [RtlPcToFileHeader](/windows/desktop/api/WinNT/nf-winnt-rtlpctofileheader)
#### [RtlUnwind](/windows/desktop/api/WinNT/nf-winnt-rtlunwind)
#### [RtlUnwind2](/windows/desktop/api/WinNT/nf-winnt-rtlunwind2)
#### [RtlUnwindEx](/windows/desktop/api/WinNT/nf-winnt-rtlunwindex)
#### [RtlVirtualUnwind](/windows/desktop/api/WinNT/nf-winnt-rtlvirtualunwind)
#### [SetErrorMode](/windows/desktop/api/WinBase/)
#### [SetLastError](/windows/desktop/api/WinBase/)
#### [SetLastErrorEx](/windows/desktop/api/Winuser/nf-winuser-setlasterrorex)
#### [SetThreadErrorMode](/windows/desktop/api/WinBase/)
### [Error Handling Macros](error-handling-macro.md)
#### [C_ASSERT](/windows/desktop/api/WinNT/nf-winnt-c_assert)
### [Error Handling Structures](error-handling-structures.md)
#### [FLASHWINFO](/windows/desktop/api/Winuser/ns-winuser-flashwinfo)
### [System Error Codes](system-error-codes.md)
#### [System Error Codes (0-499)](system-error-codes--0-499-.md)
#### [System Error Codes (500-999)](system-error-codes--500-999-.md)
#### [System Error Codes (1000-1299)](system-error-codes--1000-1299-.md)
#### [System Error Codes (1300-1699)](system-error-codes--1300-1699-.md)
#### [System Error Codes (1700-3999)](system-error-codes--1700-3999-.md)
#### [System Error Codes (4000-5999)](system-error-codes--4000-5999-.md)
#### [System Error Codes (6000-8199)](system-error-codes--6000-8199-.md)
#### [System Error Codes (8200-8999)](system-error-codes--8200-8999-.md)
#### [System Error Codes (9000-11999)](system-error-codes--9000-11999-.md)
#### [System Error Codes (12000-15999)](system-error-codes--12000-15999-.md)
# [Basic Debugging](basic-debugging.md)
## [About Basic Debugging](about-basic-debugging.md)
### [Debugging Terminology](debugging-terminology.md)
### [Debug Support from Process, Thread, and Exception Functions](debug-support-from-process-thread-and-exception-functions.md)
#### [Process Functions for Debugging](process-functions-for-debugging.md)
#### [Thread Functions for Debugging](thread-functions-for-debugging.md)
#### [Exception Functions for Debugging](exception-handling-functions-for-debugging.md)
## [Using Basic Debugging](using-basic-debugging.md)
### [Configuring Automatic Debugging](configuring-automatic-debugging.md)
### [Creating a Basic Debugger](creating-a-basic-debugger.md)
#### [Debugging a Running Process](debugging-a-running-process.md)
#### [Writing the Debugger's Main Loop](writing-the-debugger-s-main-loop.md)
#### [Communicating with the Debugger](communicating-with-the-debugger.md)
## [Debugging Reference](debugging-reference.md)
### [Debugging Events](debugging-events.md)
### [Debugging Functions](debugging-functions.md)
#### [CheckRemoteDebuggerPresent](/windows/desktop/api/WinBase/)
#### [ContinueDebugEvent](/windows/desktop/api/WinBase/)
#### [DebugActiveProcess](/windows/desktop/api/WinBase/)
#### [DebugActiveProcessStop](/windows/desktop/api/WinBase/)
#### [DebugBreak](/windows/desktop/api/WinBase/)
#### [DebugBreakProcess](/windows/desktop/api/WinBase/nf-winbase-debugbreakprocess)
#### [DebugSetProcessKillOnExit](/windows/desktop/api/WinBase/nf-winbase-debugsetprocesskillonexit)
#### [FatalExit](/windows/desktop/api/WinBase/nf-winbase-fatalexit)
#### [FlushInstructionCache](https://msdn.microsoft.com/en-us/library/ms679350(v=VS.85).aspx)
#### [GetThreadContext](/windows/desktop/api/WinBase/nf-dbgeng-idebugadvanced4-getthreadcontext)
#### [GetThreadSelectorEntry](/windows/desktop/api/WinBase/nf-winbase-getthreadselectorentry)
#### [IsDebuggerPresent](/windows/desktop/api/WinBase/)
#### [OutputDebugString](/windows/desktop/api/WinBase/)
#### [ReadProcessMemory](https://msdn.microsoft.com/en-us/library/ms680553(v=VS.85).aspx)
#### [SetThreadContext](/windows/desktop/api/WinBase/nf-dbgeng-idebugadvanced4-setthreadcontext)
#### [WaitForDebugEvent](/windows/desktop/api/WinBase/)
#### [WaitForDebugEventEx](/windows/desktop/api/WinBase/)
#### [Wow64GetThreadContext](/windows/desktop/api/WinBase/nf-winbase-wow64getthreadcontext)
#### [Wow64GetThreadSelectorEntry](/windows/desktop/api/WinBase/nf-winbase-wow64getthreadselectorentry)
#### [Wow64SetThreadContext](/windows/desktop/api/WinBase/nf-winbase-wow64setthreadcontext)
#### [WriteProcessMemory](https://msdn.microsoft.com/en-us/library/ms681674(v=VS.85).aspx)
### [Debugging Structures](debugging-structures.md)
#### [CONTEXT](/windows/desktop/api/WinNT/ns-winnt-_arm64_nt_context)
#### [CREATE_PROCESS_DEBUG_INFO](https://msdn.microsoft.com/en-us/library/ms679286(v=VS.85).aspx)
#### [CREATE_THREAD_DEBUG_INFO](https://msdn.microsoft.com/en-us/library/ms679287(v=VS.85).aspx)
#### [DEBUG_EVENT](https://msdn.microsoft.com/en-us/library/ms679308(v=VS.85).aspx)
#### [EXCEPTION_DEBUG_INFO](https://msdn.microsoft.com/en-us/library/ms679326(v=VS.85).aspx)
#### [EXIT_PROCESS_DEBUG_INFO](https://msdn.microsoft.com/en-us/library/ms679334(v=VS.85).aspx)
#### [EXIT_THREAD_DEBUG_INFO](https://msdn.microsoft.com/en-us/library/ms679335(v=VS.85).aspx)
#### [LDT_ENTRY](/windows/desktop/api/WinNT/ns-winnt-_ldt_entry)
#### [LOAD_DLL_DEBUG_INFO](https://msdn.microsoft.com/en-us/library/ms680351(v=VS.85).aspx)
#### [OUTPUT_DEBUG_STRING_INFO](https://msdn.microsoft.com/en-us/library/ms680545(v=VS.85).aspx)
#### [RIP_INFO](https://msdn.microsoft.com/en-us/library/ms680587(v=VS.85).aspx)
#### [Thread Environment Block (Debugging Notes)](thread-environment-block--debugging-notes-.md)
#### [UNLOAD_DLL_DEBUG_INFO](https://msdn.microsoft.com/en-us/library/ms681403(v=VS.85).aspx)
#### [WOW64_CONTEXT](/windows/desktop/api/WinNT/ns-winnt-_wow64_context)
#### [WOW64_FLOATING_SAVE_AREA](/windows/desktop/api/WinNT/ns-winnt-_wow64_floating_save_area)
#### [WOW64_LDT_ENTRY](/windows/desktop/api/WinNT/ns-winnt-_wow64_ldt_entry)
# [Debug Help Library](debug-help-library.md)
## [About DbgHelp](about-dbghelp.md)
### [DbgHelp Versions](dbghelp-versions.md)
### [Symbol Files](symbol-files.md)
### [Symbol Handling](symbol-handling.md)
#### [Symbol Handler Initialization](symbol-handler-initialization.md)
#### [Symbol Paths](symbol-paths.md)
#### [Symbol Loading](symbol-loading.md)
#### [Deferred Symbol Loading](deferred-symbol-loading.md)
#### [Decorated Symbol Names](decorated-symbol-names.md)
#### [Finding Symbols](finding-symbols.md)
#### [Public, Global, and Local Symbols](public--global--and-local-symbols.md)
#### [Symbol Handler Cleanup](symbol-handler-cleanup.md)
### [Symbol Server and Symbol Stores](symbol-servers-and-symbol-stores.md)
#### [Using SymSrv](using-symsrv.md)
#### [Using SymStore](using-symstore.md)
#### [Using Other Symbol Stores](using-other-symbol-stores.md)
#### [SymStore Command-Line Options](symstore-command-line-options.md)
#### [Symbol Server and Internet Firewalls](symbol-servers-and-internet-firewalls.md)
### [Minidump Files](minidump-files.md)
### [Source Server](source-server-and-source-indexing.md)
### [Updated Platform Support](updated-platform-support.md)
## [Using DbgHelp](using-dbghelp.md)
### [Calling the DbgHelp Library](calling-the-dbghelp-library.md)
### [Initializing the Symbol Handler](initializing-the-symbol-handler.md)
### [Loading a Symbol Module](loading-a-symbol-module.md)
### [Getting Notifications](getting-notifications.md)
### [Enumerating Symbol Modules](enumerating-symbol-modules.md)
### [Enumerating Symbols](enumerating-symbols.md)
### [Retrieving Symbol Information by Name](retrieving-symbol-information-by-name.md)
### [Retrieving Symbol Information by Address](retrieving-symbol-information-by-address.md)
### [Retrieving Undecorated Symbol Names](retrieving-undecorated-symbol-names.md)
### [Unloading a Symbol Module](unloading-a-symbol-module.md)
### [Terminating the Symbol Handler](terminating-the-symbol-handler.md)
## [DbgHelp Reference](dbghelp-reference.md)
### [DbgHelp Enumerations](dbghelp-enumerations.md)
#### [IMAGEHLP_EXTENDED_OPTIONS](/windows/desktop/api/DbgHelp/ne-dbghelp-imagehlp_extended_options)
#### [IMAGEHLP_SYMBOL_TYPE_INFO](/windows/desktop/api/DbgHelp/ne-dbghelp-_imagehlp_symbol_type_info)
#### [MINIDUMP_CALLBACK_TYPE](/windows/desktop/api/minidumpapiset/ne-minidumpapiset-_minidump_callback_type)
#### [MINIDUMP_HANDLE_OBJECT_INFORMATION_TYPE](/windows/desktop/api/minidumpapiset/ne-minidumpapiset-_minidump_handle_object_information_type)
#### [MINIDUMP_SECONDARY_FLAGS](/windows/desktop/api/minidumpapiset/ne-minidumpapiset-_minidump_secondary_flags)
#### [MINIDUMP_STREAM_TYPE](/windows/desktop/api/minidumpapiset/ne-minidumpapiset-_minidump_stream_type)
#### [MINIDUMP_TYPE](/windows/desktop/api/minidumpapiset/ne-minidumpapiset-_minidump_type)
#### [MODULE_WRITE_FLAGS](/windows/desktop/api/minidumpapiset/ne-minidumpapiset-_module_write_flags)
#### [THREAD_WRITE_FLAGS](/windows/desktop/api/minidumpapiset/ne-minidumpapiset-_thread_write_flags)
### [DbgHelp Functions](dbghelp-functions.md)
#### [EnumDirTree](/windows/desktop/api/Dbghelp/nf-dbghelp-enumdirtree)
#### [EnumDirTreeProc](/windows/desktop/api/DbgHelp/nc-dbghelp-penumdirtree_callback)
#### [EnumerateLoadedModules64](/windows/desktop/api/Dbghelp/nf-dbghelp-enumerateloadedmodules)
#### [EnumerateLoadedModulesEx](/windows/desktop/api/Dbghelp/nf-dbghelp-enumerateloadedmodulesex)
#### [EnumerateLoadedModulesProc64](/windows/desktop/api/DbgHelp/nc-dbghelp-penumloaded_modules_callback)
#### [FindDebugInfoFile](/windows/desktop/api/Dbghelp/nf-dbghelp-finddebuginfofile)
#### [FindDebugInfoFileEx](/windows/desktop/api/Dbghelp/nf-dbghelp-finddebuginfofileex)
#### [FindDebugInfoFileProc](/windows/desktop/api/DbgHelp/nc-dbghelp-pfind_debug_file_callback)
#### [FindExecutableImage](/windows/desktop/api/Dbghelp/nf-dbghelp-findexecutableimage)
#### [FindExecutableImageEx](/windows/desktop/api/Dbghelp/nf-dbghelp-findexecutableimageex)
#### [FindExecutableImageProc](/windows/desktop/api/DbgHelp/nc-dbghelp-pfind_exe_file_callback)
#### [FunctionTableAccessProc64](/windows/desktop/api/DbgHelp/nc-dbghelp-pfunction_table_access_routine)
#### [GetModuleBaseProc64](/windows/desktop/api/DbgHelp/nc-dbghelp-pget_module_base_routine)
#### [GetSymLoadError](/windows/desktop/api/DbgHelp/nf-dbghelp-getsymloaderror)
#### [GetTimestampForLoadedLibrary](/windows/desktop/api/Dbghelp/nf-dbghelp-gettimestampforloadedlibrary)
#### [ImageDirectoryEntryToData](/windows/desktop/api/Dbghelp/nf-dbghelp-imagedirectoryentrytodata)
#### [ImageDirectoryEntryToDataEx](/windows/desktop/api/Dbghelp/nf-dbghelp-imagedirectoryentrytodataex)
#### [ImagehlpApiVersion](/windows/desktop/api/Dbghelp/nf-dbghelp-imagehlpapiversion)
#### [ImagehlpApiVersionEx](/windows/desktop/api/Dbghelp/nf-dbghelp-imagehlpapiversionex)
#### [ImageNtHeader](/windows/desktop/api/Dbghelp/nf-dbghelp-imagentheader)
#### [ImageRvaToSection](/windows/desktop/api/Dbghelp/nf-dbghelp-imagervatosection)
#### [ImageRvaToVa](/windows/desktop/api/Dbghelp/nf-dbghelp-imagervatova)
#### [MakeSureDirectoryPathExists](/windows/desktop/api/Dbghelp/nf-dbghelp-makesuredirectorypathexists)
#### [MapDebugInformation](/windows/desktop/api/Dbghelp/nf-dbghelp-mapdebuginformation)
#### [MiniDumpCallback](/windows/desktop/api/minidumpapiset/nc-minidumpapiset-minidump_callback_routine)
#### [MiniDumpReadDumpStream](/windows/desktop/api/minidumpapiset/nf-minidumpapiset-minidumpreaddumpstream)
#### [MiniDumpWriteDump](/windows/desktop/api/minidumpapiset/nf-minidumpapiset-minidumpwritedump)
#### [ReadProcessMemoryProc64](/windows/desktop/api/DbgHelp/nc-dbghelp-pread_process_memory_routine)
#### [SearchTreeForFile](/windows/desktop/api/Dbghelp/nf-dbghelp-searchtreeforfile)
#### [SetSymLoadError](/windows/desktop/api/DbgHelp/nf-dbghelp-setsymloaderror)
#### [StackWalk64](/windows/desktop/api/DbgHelp/nf-dbghelp-stackwalk)
#### [StackWalkEx](/windows/desktop/api/DbgHelp/nf-dbghelp-stackwalkex)
#### [SymAddrIncludeInlineTrace](/windows/desktop/api/DbgHelp/nf-dbghelp-symaddrincludeinlinetrace)
#### [SymAddSourceStream](/windows/desktop/api/Dbghelp/nf-dbghelp-symaddsourcestream)
#### [SymAddSymbol](/windows/desktop/api/Dbghelp/nf-dbghelp-symaddsymbol)
#### [SymCleanup](/windows/desktop/api/Dbghelp/nf-dbghelp-symcleanup)
#### [SymCompareInlineTrace](/windows/desktop/api/DbgHelp/nf-dbghelp-symcompareinlinetrace)
#### [SymDeleteSymbol](/windows/desktop/api/Dbghelp/nf-dbghelp-symdeletesymbol)
#### [SymEnumerateModules64](/windows/desktop/api/Dbghelp/nf-dbghelp-symenumeratemodules)
#### [SymEnumerateModulesProc64](/windows/desktop/api/DbgHelp/nc-dbghelp-psym_enummodules_callback)
#### [SymEnumerateSymbols64](/windows/desktop/api/Dbghelp/nf-dbghelp-symenumeratesymbols)
#### [SymEnumerateSymbolsProc64](/windows/desktop/api/DbgHelp/nc-dbghelp-psym_enumsymbols_callback)
#### [SymEnumLines](/windows/desktop/api/Dbghelp/nf-dbghelp-symenumlines)
#### [SymEnumLinesProc](/windows/desktop/api/DbgHelp/nc-dbghelp-psym_enumlines_callback)
#### [SymEnumProcesses](/windows/desktop/api/DbgHelp/nf-dbghelp-symenumprocesses)
#### [SymEnumProcessesProc](/windows/desktop/api/DbgHelp/nc-dbghelp-psym_enumprocesses_callback)
#### [SymEnumSourceFiles](/windows/desktop/api/DbgHelp/nf-dbghelp-symenumsourcefiles)
#### [SymEnumSourceFilesProc](/windows/desktop/api/DbgHelp/nc-dbghelp-psym_enumsourcefiles_callback)
#### [SymEnumSourceFileTokens](/windows/desktop/api/Dbghelp/nf-dbghelp-symenumsourcefiletokens)
#### [PENUMSOURCEFILETOKENSCALLBACK](/windows/desktop/api/Dbghelp/nc-dbghelp-penumsourcefiletokenscallback)
#### [SymEnumSourceLines](/windows/desktop/api/DbgHelp/nf-dbghelp-symenumsourcelines)
#### [SymEnumSymbols](/windows/desktop/api/Dbghelp/nf-dbghelp-symenumsymbols)
#### [SymEnumSymbolsEx](/windows/desktop/api/DbgHelp/nf-dbghelp-symenumsymbolsex)
#### [SymEnumSymbolsForAddr](/windows/desktop/api/Dbghelp/nf-dbghelp-symenumsymbolsforaddr)
#### [SymEnumSymbolsProc](/windows/desktop/api/DbgHelp/nc-dbghelp-psym_enumeratesymbols_callback)
#### [SymEnumTypes](/windows/desktop/api/Dbghelp/nf-dbghelp-symenumtypes)
#### [SymEnumTypesByName](/windows/desktop/api/Dbghelp/nf-dbghelp-symenumtypesbyname)
#### [SymFindDebugInfoFile](/windows/desktop/api/Dbghelp/nf-dbghelp-symfinddebuginfofile)
#### [SymFindExecutableImage](/windows/desktop/api/Dbghelp/nf-dbghelp-symfindexecutableimage)
#### [SymFindFileInPath](/windows/desktop/api/DbgHelp/nf-dbghelp-symfindfileinpath)
#### [SymFindFileInPathProc](/windows/desktop/api/DbgHelp/nc-dbghelp-pfindfileinpathcallback)
#### [SymFromAddr](/windows/desktop/api/Dbghelp/nf-dbghelp-symfromaddr)
#### [SymFromIndex](/windows/desktop/api/Dbghelp/nf-dbghelp-symfromindex)
#### [SymFromInlineContext](/windows/desktop/api/DbgHelp/nf-dbghelp-symfrominlinecontext)
#### [SymFromName](/windows/desktop/api/Dbghelp/nf-dbghelp-symfromname)
#### [SymFromToken](/windows/desktop/api/Dbghelp/nf-dbghelp-symfromtoken)
#### [SymFunctionTableAccess64](/windows/desktop/api/Dbghelp/nf-dbghelp-symfunctiontableaccess)
#### [SymFunctionTableAccess64AccessRoutines](/windows/desktop/api/DbgHelp/nf-dbghelp-symfunctiontableaccess64accessroutines)
#### [SymGetExtendedOption](/windows/desktop/api/DbgHelp/nf-dbghelp-symgetextendedoption)
#### [SymGetFileLineOffsets64](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetfilelineoffsets64)
#### [SymGetHomeDirectory](/windows/desktop/api/Dbghelp/nf-dbghelp-symgethomedirectory)
#### [SymGetLineFromAddr64](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetlinefromaddr)
#### [SymGetLineFromInlineContext](/windows/desktop/api/DbgHelp/nf-dbghelp-symgetlinefrominlinecontext)
#### [SymGetLineFromName64](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetlinefromname)
#### [SymGetLineNext64](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetlinenext)
#### [SymGetLinePrev64](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetlineprev)
#### [SymGetModuleBase64](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetmodulebase)
#### [SymGetModuleInfo64](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetmoduleinfo)
#### [SymGetOmaps](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetomaps)
#### [SymGetOptions](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetoptions)
#### [SymGetScope](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetscope)
#### [SymGetSearchPath](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetsearchpath)
#### [SymGetSourceFile](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetsourcefile)
#### [SymGetSourceFileChecksum](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetsourcefilechecksum)
#### [SymGetSourceFileFromToken](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetsourcefilefromtoken)
#### [SymGetSourceFileToken](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetsourcefiletoken)
#### [SymGetSourceVarFromToken](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetsourcevarfromtoken)
#### [SymGetSymbolFile](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetsymbolfile)
#### [SymGetSymFromAddr64](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetsymfromaddr)
#### [SymGetSymFromName64](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetsymfromname)
#### [SymGetSymNext64](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetsymnext)
#### [SymGetSymPrev64](/windows/desktop/api/Dbghelp/nf-dbghelp-symgetsymprev)
#### [SymGetTypeFromName](/windows/desktop/api/Dbghelp/nf-dbghelp-symgettypefromname)
#### [SymGetTypeInfo](/windows/desktop/api/Dbghelp/nf-dbghelp-symgettypeinfo)
#### [SymGetTypeInfoEx](/windows/desktop/api/Dbghelp/nf-dbghelp-symgettypeinfoex)
#### [SymInitialize](/windows/desktop/api/Dbghelp/nf-dbghelp-syminitialize)
#### [SymLoadModule64](/windows/desktop/api/Dbghelp/nf-dbghelp-symloadmodule)
#### [SymLoadModuleEx](/windows/desktop/api/Dbghelp/nf-dbghelp-symloadmoduleex)
#### [SymMatchFileName](/windows/desktop/api/Dbghelp/nf-dbghelp-symmatchfilename)
#### [SymMatchString](/windows/desktop/api/DbgHelp/nf-dbghelp-symmatchstring)
#### [SymNext](/windows/desktop/api/DbgHelp/nf-dbghelp-symnext)
#### [SymPrev](/windows/desktop/api/DbgHelp/nf-dbghelp-symprev)
#### [SymQueryInlineTrace](/windows/desktop/api/DbgHelp/nf-dbghelp-symqueryinlinetrace)
#### [SymRefreshModuleList](/windows/desktop/api/Dbghelp/nf-dbghelp-symrefreshmodulelist)
#### [SymRegisterCallback64](/windows/desktop/api/Dbghelp/nf-dbghelp-symregistercallback)
#### [SymRegisterCallbackProc64](/windows/desktop/api/DbgHelp/nc-dbghelp-psymbol_registered_callback)
#### [SymRegisterFunctionEntryCallback64](/windows/desktop/api/Dbghelp/nf-dbghelp-symregisterfunctionentrycallback)
#### [SymRegisterFunctionEntryCallbackProc64](/windows/desktop/api/DbgHelp/nc-dbghelp-psymbol_funcentry_callback)
#### [SymSearch](/windows/desktop/api/Dbghelp/nf-dbghelp-symsearch)
#### [SymSetContext](/windows/desktop/api/Dbghelp/nf-dbghelp-symsetcontext)
#### [SymSetExtendedOption](/windows/desktop/api/DbgHelp/nf-dbghelp-symsetextendedoption)
#### [SymSetHomeDirectory](/windows/desktop/api/Dbghelp/nf-dbghelp-symsethomedirectory)
#### [SymSetOptions](/windows/desktop/api/Dbghelp/nf-dbghelp-symsetoptions)
#### [SymSetParentWindow](/windows/desktop/api/Dbghelp/nf-dbghelp-symsetparentwindow)
#### [SymSetScopeFromAddr](/windows/desktop/api/Dbghelp/nf-dbghelp-symsetscopefromaddr)
#### [SymSetScopeFromIndex](/windows/desktop/api/Dbghelp/nf-dbghelp-symsetscopefromindex)
#### [SymSetScopeFromInlineContext](/windows/desktop/api/DbgHelp/nf-dbghelp-symsetscopefrominlinecontext)
#### [SymSetSearchPath](/windows/desktop/api/Dbghelp/nf-dbghelp-symsetsearchpath)
#### [SymSrvDeltaName](/windows/desktop/api/DbgHelp/nf-dbghelp-symsrvdeltaname)
#### [SymSrvGetFileIndexes](/windows/desktop/api/DbgHelp/nf-dbghelp-symsrvgetfileindexes)
#### [SymSrvGetFileIndexInfo](/windows/desktop/api/Dbghelp/nf-dbghelp-symsrvgetfileindexinfo)
#### [SymSrvGetFileIndexString](/windows/desktop/api/DbgHelp/nf-dbghelp-symsrvgetfileindexstring)
#### [SymSrvGetSupplement](/windows/desktop/api/DbgHelp/nf-dbghelp-symsrvgetsupplement)
#### [SymSrvIsStore](/windows/desktop/api/DbgHelp/nf-dbghelp-symsrvisstore)
#### [SymSrvStoreFile](/windows/desktop/api/DbgHelp/nf-dbghelp-symsrvstorefile)
#### [SymSrvStoreSupplement](/windows/desktop/api/DbgHelp/nf-dbghelp-symsrvstoresupplement)
#### [SymUnDName64](/windows/desktop/api/Dbghelp/nf-dbghelp-symundname)
#### [SymUnloadModule64](/windows/desktop/api/Dbghelp/nf-dbghelp-symunloadmodule)
#### [TranslateAddressProc64](/windows/desktop/api/DbgHelp/nc-dbghelp-ptranslate_address_routine)
#### [UnDecorateSymbolName](/windows/desktop/api/Dbghelp/nf-dbghelp-undecoratesymbolname)
#### [UnmapDebugInformation](/windows/desktop/api/Dbghelp/nf-dbghelp-unmapdebuginformation)
### [DbgHelp Structures](dbghelp-structures.md)
#### [_IMAGE_RUNTIME_FUNCTION_ENTRY](/windows/desktop/api/WinNT/ns-winnt-_image_runtime_function_entry)
#### [ADDRESS64](/windows/desktop/api/DbgHelp/ns-dbghelp-_tagaddress)
#### [API_VERSION](/windows/desktop/api/DbgHelp/ns-dbghelp-api_version)
#### [FPO_DATA](/windows/desktop/api/WinNT/ns-winnt-_fpo_data)
#### [IMAGE_DEBUG_INFORMATION](/windows/desktop/api/DbgHelp/ns-dbghelp-_image_debug_information)
#### [IMAGEHLP_CBA_EVENT](/windows/desktop/api/DbgHelp/ns-dbghelp-_imagehlp_cba_event)
#### [IMAGEHLP_CBA_READ_MEMORY](/windows/desktop/api/DbgHelp/ns-dbghelp-_imagehlp_cba_read_memory)
#### [IMAGEHLP_DEFERRED_SYMBOL_LOAD64](/windows/desktop/api/DbgHelp/ns-dbghelp-_imagehlp_deferred_symbol_load)
#### [IMAGEHLP_DUPLICATE_SYMBOL64](/windows/desktop/api/DbgHelp/ns-dbghelp-_imagehlp_duplicate_symbol)
#### [IMAGEHLP_GET_TYPE_INFO_PARAMS](/windows/desktop/api/DbgHelp/ns-dbghelp-_imagehlp_get_type_info_params)
#### [IMAGEHLP_LINE64](/windows/desktop/api/DbgHelp/ns-dbghelp-_imagehlp_line)
#### [IMAGEHLP_MODULE64](/windows/desktop/api/DbgHelp/ns-dbghelp-_imagehlp_module)
#### [IMAGEHLP_STACK_FRAME](/windows/desktop/api/DbgHelp/ns-dbghelp-_imagehlp_stack_frame)
#### [IMAGEHLP_SYMBOL64](/windows/desktop/api/DbgHelp/ns-dbghelp-_imagehlp_symbol)
#### [KDHELP64](/windows/desktop/api/DbgHelp/ns-dbghelp-_kdhelp)
#### [LOADED_IMAGE](/windows/desktop/api/DbgHelp/ns-dbghelp-_loaded_image)
#### [MINIDUMP_CALLBACK_INFORMATION](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_callback_information)
#### [MINIDUMP_CALLBACK_INPUT](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_callback_input)
#### [MINIDUMP_CALLBACK_OUTPUT](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_callback_output)
#### [MINIDUMP_DIRECTORY](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_directory)
#### [MINIDUMP_EXCEPTION](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_exception)
#### [MINIDUMP_EXCEPTION_INFORMATION](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_exception_information)
#### [MINIDUMP_EXCEPTION_STREAM](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-minidump_exception_stream)
#### [MINIDUMP_FUNCTION_TABLE_DESCRIPTOR](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_function_table_descriptor)
#### [MINIDUMP_FUNCTION_TABLE_STREAM](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_function_table_stream)
#### [MINIDUMP_HANDLE_DATA_STREAM](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_handle_data_stream)
#### [MINIDUMP_HANDLE_DESCRIPTOR](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_handle_descriptor)
#### [MINIDUMP_HANDLE_DESCRIPTOR_2](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_handle_descriptor_2)
#### [MINIDUMP_HANDLE_OBJECT_INFORMATION](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_handle_object_information)
#### [MINIDUMP_HANDLE_OPERATION_LIST](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_handle_operation_list)
#### [MINIDUMP_HEADER](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_header)
#### [MINIDUMP_INCLUDE_MODULE_CALLBACK](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_include_module_callback)
#### [MINIDUMP_INCLUDE_THREAD_CALLBACK](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_include_thread_callback)
#### [MINIDUMP_IO_CALLBACK](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_io_callback)
#### [MINIDUMP_LOCATION_DESCRIPTOR](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_location_descriptor)
#### [MINIDUMP_MEMORY_DESCRIPTOR](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_memory_descriptor)
#### [MINIDUMP_MEMORY_INFO](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_memory_info)
#### [MINIDUMP_MEMORY_INFO_LIST](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_memory_info_list)
#### [MINIDUMP_MEMORY_LIST](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_memory64_list)
#### [MINIDUMP_MISC_INFO](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_misc_info)
#### [MINIDUMP_MISC_INFO_2](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_misc_info_2)
#### [MINIDUMP_MODULE](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_module)
#### [MINIDUMP_MODULE_CALLBACK](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_module_callback)
#### [MINIDUMP_MODULE_LIST](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_module_list)
#### [MINIDUMP_READ_MEMORY_FAILURE_CALLBACK](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_read_memory_failure_callback)
#### [MINIDUMP_STRING](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_string)
#### [MINIDUMP_SYSTEM_INFO](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_system_info)
#### [MINIDUMP_THREAD](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_thread)
#### [MINIDUMP_THREAD_CALLBACK](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_thread_callback)
#### [MINIDUMP_THREAD_EX](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_thread_ex)
#### [MINIDUMP_THREAD_EX_CALLBACK](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_thread_ex_callback)
#### [MINIDUMP_THREAD_EX_LIST](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_thread_ex_list)
#### [MINIDUMP_THREAD_INFO](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_thread_info)
#### [MINIDUMP_THREAD_INFO_LIST](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_thread_info_list)
#### [MINIDUMP_THREAD_LIST](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_thread_list)
#### [MINIDUMP_UNLOADED_MODULE](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_unloaded_module)
#### [MINIDUMP_UNLOADED_MODULE_LIST](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_unloaded_module_list)
#### [MINIDUMP_USER_STREAM](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_user_stream)
#### [MINIDUMP_USER_STREAM_INFORMATION](/windows/desktop/api/minidumpapiset/ns-minidumpapiset-_minidump_user_stream_information)
#### [MODLOAD_CVMISC](/windows/desktop/api/DbgHelp/ns-dbghelp-_modload_cvmisc)
#### [MODLOAD_DATA](/windows/desktop/api/DbgHelp/ns-dbghelp-_modload_data)
#### [OMAP](/windows/desktop/api/Dbghelp/ns-dbghelp-_omap)
#### [SOURCEFILE](/windows/desktop/api/DbgHelp/ns-dbghelp-_sourcefile)
#### [SRCCODEINFO](/windows/desktop/api/DbgHelp/ns-dbghelp-_srccodeinfo)
#### [STACKFRAME64](/windows/desktop/api/DbgHelp/ns-dbghelp-_tagstackframe)
#### [STACKFRAME_EX](/windows/desktop/api/DbgHelp/ns-dbghelp-_tagstackframe_ex)
#### [SYMBOL_INFO](/windows/desktop/api/DbgHelp/ns-dbghelp-_symbol_info)
#### [SYMSRV_INDEX_INFO](/windows/desktop/api/Dbghelp/ns-dbghelp-symsrv_index_info)
#### [TI_FINDCHILDREN_PARAMS](/windows/desktop/api/DbgHelp/ns-dbghelp-_ti_findchildren_params)
### [Image Help Library](image-help-library.md)
#### [About ImageHlp](about-imagehlp.md)
##### [PE Format](pe-format.md)
##### [Image Access Functions](image-access-functions.md)
##### [ImageHlp Image Integrity Functions](image-integrity-functions.md)
##### [ImageHlp Image Modification Functions](image-modification-functions.md)
#### [ImageHlp Reference](imagehlp-reference.md)
##### [ImageHlp Functions](imagehlp-functions.md)
###### [BindImage](/windows/desktop/api/Imagehlp/nf-imagehlp-bindimage)
###### [BindImageEx](/windows/desktop/api/Imagehlp/nf-imagehlp-bindimageex)
###### [CheckSumMappedFile](/windows/desktop/api/Imagehlp/nf-imagehlp-checksummappedfile)
###### [DigestFunction](/windows/desktop/api/Imagehlp/nc-imagehlp-digest_function)
###### [GetImageConfigInformation](/windows/desktop/api/Imagehlp/nf-imagehlp-getimageconfiginformation)
###### [GetImageUnusedHeaderBytes](/windows/desktop/api/Imagehlp/nf-imagehlp-getimageunusedheaderbytes)
###### [ImageAddCertificate](/windows/desktop/api/Imagehlp/nf-imagehlp-imageaddcertificate)
###### [ImageEnumerateCertificates](/windows/desktop/api/Imagehlp/nf-imagehlp-imageenumeratecertificates)
###### [ImageGetCertificateData](/windows/desktop/api/Imagehlp/nf-imagehlp-imagegetcertificatedata)
###### [ImageGetCertificateHeader](/windows/desktop/api/Imagehlp/nf-imagehlp-imagegetcertificateheader)
###### [ImageGetDigestStream](/windows/desktop/api/Imagehlp/nf-imagehlp-imagegetdigeststream)
###### [ImageLoad](/windows/desktop/api/Imagehlp/nf-imagehlp-imageload)
###### [ImageRemoveCertificate](/windows/desktop/api/Imagehlp/nf-imagehlp-imageremovecertificate)
###### [ImageUnload](/windows/desktop/api/Imagehlp/nf-imagehlp-imageunload)
###### [MapAndLoad](/windows/desktop/api/Imagehlp/nf-imagehlp-mapandload)
###### [MapFileAndCheckSum](/windows/desktop/api/Imagehlp/nf-imagehlp-mapfileandchecksuma)
###### [ReBaseImage](/windows/desktop/api/Imagehlp/nf-imagehlp-rebaseimage)
###### [ReBaseImage64](/windows/desktop/api/Imagehlp/nf-imagehlp-rebaseimage64)
###### [SetImageConfigInformation](/windows/desktop/api/Imagehlp/nf-imagehlp-setimageconfiginformation)
###### [SplitSymbols](/windows/desktop/api/Imagehlp/nf-imagehlp-splitsymbols)
###### [StatusRoutine](/windows/desktop/api/Imagehlp/nc-imagehlp-pimagehlp_status_routine)
###### [TouchFileTimes](/windows/desktop/api/Imagehlp/nf-imagehlp-touchfiletimes)
###### [UnMapAndLoad](/windows/desktop/api/Imagehlp/nf-imagehlp-unmapandload)
###### [UpdateDebugInfoFile](/windows/desktop/api/Imagehlp/nf-imagehlp-updatedebuginfofile)
###### [UpdateDebugInfoFileEx](/windows/desktop/api/Imagehlp/nf-imagehlp-updatedebuginfofileex)
##### [ImageHlp Structures](imagehlp-structures.md)
###### [IMAGE_COFF_SYMBOLS_HEADER](/windows/desktop/api/WinNT/ns-winnt-_image_coff_symbols_header)
###### [IMAGE_DATA_DIRECTORY](/windows/desktop/api/WinNT/ns-winnt-_image_data_directory)
###### [IMAGE_DEBUG_DIRECTORY](/windows/desktop/api/WinNT/ns-winnt-_image_debug_directory)
###### [IMAGE_FILE_HEADER](/windows/desktop/api/WinNT/ns-winnt-_image_file_header)
###### [IMAGE_FUNCTION_ENTRY](/windows/desktop/api/WinNT/ns-winnt-_image_function_entry)
###### [IMAGE_LOAD_CONFIG_DIRECTORY64](/windows/desktop/api/WinNT/ns-winnt-_image_load_config_directory32)
###### [IMAGE_NT_HEADERS](/windows/desktop/api/WinNT/ns-winnt-_image_nt_headers)
###### [IMAGE_OPTIONAL_HEADER](/windows/desktop/api/WinNT/ns-winnt-_image_optional_header)
###### [IMAGE_SECTION_HEADER](/windows/desktop/api/WinNT/ns-winnt-_image_section_header)
# [Structured Exception Handling](structured-exception-handling.md)
## [About Structured Exception Handling](about-structured-exception-handling.md)
### [Exception Handling](exception-handling.md)
#### [Exception Dispatching](exception-dispatching.md)
#### [Debugger Exception Handling](debugger-exception-handling.md)
#### [Floating-Point Exceptions](floating-point-exceptions.md)
### [Frame-based Exception Handling](frame-based-exception-handling.md)
### [Vectored Exception Handling](vectored-exception-handling.md)
### [Termination Handling](termination-handling.md)
### [Handler Syntax](handler-syntax.md)
#### [Exception-Handler Syntax](exception-handler-syntax.md)
#### [Termination-Handler Syntax](termination-handler-syntax.md)
## [Using Structured Exception Handling](using-structured-exception-handling.md)
### [Using an Exception Handler](using-an-exception-handler.md)
### [Using a Termination Handler](using-a-termination-handler.md)
### [Using a Vectored Exception Handler](using-a-vectored-exception-handler.md)
## [Structured Exception Handling Reference](structured-exception-handling-reference.md)
### [Structured Exception Handling Functions](structured-exception-handling-functions.md)
#### [AbnormalTermination](abnormaltermination.md)
#### [AddVectoredContinueHandler](/windows/desktop/api/WinBase/)
#### [AddVectoredExceptionHandler](/windows/desktop/api/WinBase/)
#### [GetExceptionCode](getexceptioncode.md)
#### [GetExceptionInformation](getexceptioninformation.md)
#### [RaiseException](/windows/desktop/api/WinBase/)
#### [RaiseFailFastException](/windows/desktop/api/WinBase/)
#### [RemoveVectoredContinueHandler](/windows/desktop/api/WinBase/)
#### [RemoveVectoredExceptionHandler](/windows/desktop/api/WinBase/)
#### [RtlAddFunctionTable](/windows/desktop/api/WinNT/nf-winnt-rtladdfunctiontable)
#### [RtlAddGrowableFunctionTable](/windows/desktop/api/WinNT/nf-winnt-rtladdgrowablefunctiontable)
#### [RtlCaptureContext](/windows/desktop/api/WinNT/nf-winnt-rtlcapturecontext)
#### [RtlDeleteFunctionTable](/windows/desktop/api/WinNT/nf-winnt-rtldeletefunctiontable)
#### [RtlDeleteGrowableFunctionTable](/windows/desktop/api/WinNT/nf-winnt-rtldeletegrowablefunctiontable)
#### [RtlGrowFunctionTable](/windows/desktop/api/WinNT/nf-winnt-rtlgrowfunctiontable)
#### [RtlInstallFunctionTableCallback](/windows/desktop/api/WinNT/nf-winnt-rtlinstallfunctiontablecallback)
#### [RtlRestoreContext](/windows/desktop/api/WinNT/nf-winnt-rtlrestorecontext)
#### [SetUnhandledExceptionFilter](/windows/desktop/api/WinBase/)
#### [UnhandledExceptionFilter](/windows/desktop/api/WinBase/)
#### [VectoredHandler](/windows/desktop/api/WinNT/nc-winnt-pvectored_exception_handler)
### [Structured Exception Handling Structures](structured-exception-handling-structures.md)
#### [EXCEPTION_POINTERS](/windows/desktop/api/WinNT/ns-winnt-_exception_pointers)
#### [EXCEPTION_RECORD](/windows/desktop/api/WinNT/ns-winnt-_exception_record)
# [Wait Chain Traversal](wait-chain-traversal.md)
## [Using WCT](using-wct.md)
## [WCT Reference](wct-reference.md)
### [CloseThreadWaitChainSession](/windows/desktop/api/Wct/nf-wct-closethreadwaitchainsession)
### [GetThreadWaitChain](/windows/desktop/api/Wct/nf-wct-getthreadwaitchain)
### [OpenThreadWaitChainSession](/windows/desktop/api/Wct/nf-wct-openthreadwaitchainsession)
### [RegisterWaitChainCOMCallback](/windows/desktop/api/Wct/nf-wct-registerwaitchaincomcallback)
### [WAITCHAIN_NODE_INFO](/windows/desktop/api/Wct/ns-wct-_waitchain_node_info)
### [PWAITCHAINCALLBACK](/windows/desktop/api/Wct/nc-wct-pwaitchaincallback)
# [Intel AVX](avx-support-portal.md)
## [Working with XState Context](working-with-xstate-context.md)
## [AVX Functions](avx-functions.md)
### [CopyContext](/windows/desktop/api/WinBase/nf-winbase-copycontext)
### [GetEnabledXStateFeatures](/windows/desktop/api/WinBase/nf-winbase-getenabledxstatefeatures)
### [GetXStateFeaturesMask](/windows/desktop/api/WinBase/nf-winbase-getxstatefeaturesmask)
### [InitializeContext](/windows/desktop/api/WinBase/nf-winbase-initializecontext)
### [LocateXStateFeature](/windows/desktop/api/WinBase/nf-winbase-locatexstatefeature)
### [SetXStateFeaturesMask](/windows/desktop/api/WinBase/nf-winbase-setxstatefeaturesmask)
