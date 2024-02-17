powershell 
Get-MpComputerStatus
Update-MpSignature
Update-MpSignature -UpdateSource SourceName
Set-MpPreference -SignatureScheduleDay Everyday
Start-MpScan -ScanType QuickScan
Start-MpScan -ScanType FullScan
Start-MpScan -ScanType FullScan -AsJob
Start-MpWDOScan
Set-MpPreference -ScanScheduleQuickScanTime Scan_Time
Set-MpPreference -ScanScheduleQuickScanTime 14:00:00
Set-MpPreference -ScanParameters 2
Set-MpPreference -RemediationScheduleDay Scan_Day
Set-MpPreference -RemediationScheduleTime Scan_Time
