# WebsiteStatus-WorkerService
A windows worker service that check the websites status using a worker service running in the background.

##Commands
>powershell

>sc.exe create UptimeChecker2 binpath= F:\CODEs\C#_DOTNET\UptimeCheckerWorkerService\release\UptimeCheckerWorkerService.exe start= auto

sc.exe delete UptimeChecker
