# HorizonDEMOfficeConfigurations
These are the configurations needed in VMware Horizon DEM to keep the default office configurations and credentials including Modern/Basic Authentication

# Microsoft Teams
[IncludeFolderTrees]
<LocalAppData>\Microsoft\Teams
<LocalAppData>\Microsoft\TeamsMeetingAddin
<LocalAppData>\Microsoft\TeamsPresenceAddin
<LocalAppData>\SquirrelTemp
<AppData>\Microsoft\Teams
<AppData>\Microsoft Teams
<AppData>\Teams

[IncludeRegistryTrees]
HKCU\Software\Microsoft\Office\Teams
HKCU\Software\Microsoft\Tracing\WPPMediaPerApp\Teams

[ExcludeFolderTrees]
<AppData>\Teams\logs
<AppData>\Microsoft Teams\logs
<AppData>\Microsoft\Teams\media-stack
<AppData>\Microsoft\Teams\Service Worker
<AppData>\Microsoft\Teams\Application Cache
<AppData>\Microsoft\Teams\tmp
<AppData>\Microsoft\Teams\meeting-addin\Cache

[ExcludeFiles]
<AppData>\Microsoft\Teams\*.txt
<AppData>\Microsoft\Teams\lockfile
<LocalAppData>\SquirrelTemp\SquirrelSetup.log

# OneDrive for Business
[IncludeFolderTrees]
<LocalAppData>\Microsoft\OneDrive

[IncludeRegistryTrees]
HKCU\Software\Microsoft\OneDrive
HKCU\Software\SyncEngines\Providers\OneDrive
HKCU\Software\Microsoft\Office\16.0\Groove
HKCU\Software\Microsoft\Office\16.0\SyncCenter
HKCU\Software\Microsoft\Office\16.0\SyncProc
HKCU\Software\Microsoft\Office\16.0\Workspaces

# Shared Settings
[IncludeRegistryTrees]
HKCU\Software\Microsoft\Office\16.0\Common
HKCU\Software\Microsoft\Office\16.0\FirstRun
HKCU\Software\Microsoft\Office\16.0\Microsoft Office 2016
HKCU\Software\Microsoft\Office\16.0\Registration
HKCU\Software\Microsoft\Office\16.0\User Settings
HKCU\Software\Microsoft\Office\Common
HKCU\Software\Microsoft\Shared Tools\Proofing Tools
HKCU\Software\Microsoft\VBA
HKCU\SOFTWARE\Microsoft\VSTO
HKCU\Software\Microsoft\AuthCookies
HKCU\Software\Microsoft\Windows NT\CurrentVersion\TokenBroker

[IncludeFolderTrees]
<AppData>\Microsoft\AddIns
<AppData>\Microsoft\Bibliography
<AppData>\Microsoft\Office
<AppData>\Microsoft\Proof
<AppData>\Microsoft\Spelling
<AppData>\Microsoft\Templates
<AppData>\Microsoft\UProof
<LocalAppData>\Microsoft\Office\ONetConfig
<LocalAppData>\Microsoft\Office\16.0\Licensing
<LocalAppData>\Microsoft\Office\
<LocalAppData>\Microsoft\Credentials
<LocalAppData>\Packages\Microsoft.AAD.BrokerPlugin_cw5n1h2txyewy
<LocalAppData>\Microsoft\IdentityCache
<LocalAppData>\Microsoft\OneAuth
<LocalAppData>\Microsoft\TokenBroker

[ExcludeFolderTrees]
<AppData>\Microsoft\Templates\LiveContent
<LocalAppData>\Packages\Microsoft.AAD.BrokerPlugin_cw5n1h2txyewy\TempState

[ExcludeRegistryTrees]
HKCU\Software\Microsoft\Office\16.0\Common\Identity

