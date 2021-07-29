# 🤖 AutoVT

Automate your hash checks in VirusTotal Via Powershell and APIs!!!


Powershell script to scan multiple malware hashes in VT and check your AV vendor detection status.

>>Add your malware hashes in HashList.txt file
>>Change vendor name in "{$_.Engine -eq 'TrendMicro'}" and "Out-File -FilePath Trend_detection.txt" to match against different vendors

Script will generate an output file in CSV format with detection details
Usage:
powershell.exe -noprofile -executionpolicy bypass -file .\Auto_VT.ps1
