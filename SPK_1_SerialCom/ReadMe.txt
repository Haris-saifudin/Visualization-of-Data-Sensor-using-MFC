================================================================================
    MICROSOFT FOUNDATION CLASS LIBRARY : SPK_1_SerialCom Project Overview
===============================================================================

The application wizard has created this SPK_1_SerialCom application for
you.  This application not only demonstrates the basics of using the Microsoft
Foundation Classes but is also a starting point for writing your application.

This file contains a summary of what you will find in each of the files that
make up your SPK_1_SerialCom application.

SPK_1_SerialCom.vcxproj
    This is the main project file for VC++ projects generated using an application wizard.
    It contains information about the version of Visual C++ that generated the file, and
    information about the platforms, configurations, and project features selected with the
    application wizard.

SPK_1_SerialCom.vcxproj.filters
    This is the filters file for VC++ projects generated using an Application Wizard. 
    It contains information about the association between the files in your project 
    and the filters. This association is used in the IDE to show grouping of files with
    similar extensions under a specific node (for e.g. ".cpp" files are associated with the
    "Source Files" filter).

SPK_1_SerialCom.h
    This is the main header file for the application.  It includes other
    project specific headers (including Resource.h) and declares the
    CSPK_1_SerialComApp application class.

SPK_1_SerialCom.cpp
    This is the main application source file that contains the application
    class CSPK_1_SerialComApp.

SPK_1_SerialCom.rc
    This is a listing of all of the Microsoft Windows resources that the
    program uses.  It includes the icons, bitmaps, and cursors that are stored
    in the RES subdirectory.  This file can be directly edited in Microsoft
    Visual C++. Your project resources are in 1033.

res\SPK_1_SerialCom.ico
    This is an icon file, which is used as the application's icon.  This
    icon is included by the main resource file SPK_1_SerialCom.rc.

res\SPK_1_SerialCom.rc2
    This file contains resources that are not edited by Microsoft
    Visual C++. You should place all resources not editable by
    the resource editor in this file.

SPK_1_SerialCom.reg
    This is an example .reg file that shows you the kind of registration
    settings the framework will set for you.  You can use this as a .reg
    file to go along with your application.

SPK_1_SerialCom.idl
    This file contains the Interface Description Language source code for the
    type library of your application.


/////////////////////////////////////////////////////////////////////////////

The application wizard creates one dialog class and automation proxy class:

SPK_1_SerialComDlg.h, SPK_1_SerialComDlg.cpp - the dialog
    These files contain your CSPK_1_SerialComDlg class.  This class defines
    the behavior of your application's main dialog.  The dialog's template is
    in SPK_1_SerialCom.rc, which can be edited in Microsoft Visual C++.

DlgProxy.h, DlgProxy.cpp - the automation object
    These files contain your CSPK_1_SerialComDlgAutoProxy class.  This class
    is called the Automation proxy class for your dialog, because it
    takes care of exposing the Automation methods and properties that
    Automation controllers can use to access your dialog.  These methods
    and properties are not exposed from the dialog class directly, because
    in the case of a modal dialog-based MFC application it is cleaner and
    easier to keep the Automation object separate from the user interface.

/////////////////////////////////////////////////////////////////////////////

Other Features:

ActiveX Controls
    The application includes support to use ActiveX controls.

Windows Sockets
    The application has support for establishing communications over TCP/IP networks.

/////////////////////////////////////////////////////////////////////////////

Other standard files:

StdAfx.h, StdAfx.cpp
    These files are used to build a precompiled header (PCH) file
    named SPK_1_SerialCom.pch and a precompiled types file named StdAfx.obj.

Resource.h
    This is the standard header file, which defines new resource IDs.
    Microsoft Visual C++ reads and updates this file.

SPK_1_SerialCom.manifest
	Application manifest files are used by Windows XP to describe an applications
	dependency on specific versions of Side-by-Side assemblies. The loader uses this
	information to load the appropriate assembly from the assembly cache or private
	from the application. The Application manifest  maybe included for redistribution
	as an external .manifest file that is installed in the same folder as the application
	executable or it may be included in the executable in the form of a resource.
/////////////////////////////////////////////////////////////////////////////

Other notes:

The application wizard uses "TODO:" to indicate parts of the source code you
should add to or customize.

If your application uses MFC in a shared DLL, you will need
to redistribute the MFC DLLs. If your application is in a language
other than the operating system's locale, you will also have to
redistribute the corresponding localized resources mfc110XXX.DLL.
For more information on both of these topics, please see the section on
redistributing Visual C++ applications in MSDN documentation.

/////////////////////////////////////////////////////////////////////////////
