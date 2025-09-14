

<img width="638" height="341" alt="image" src="https://github.com/user-attachments/assets/1faa2a5e-11ec-490d-bee3-bfe224e0f74a" />





To compile:
```
dotnet publish -c Release -r win-x64 -p:SelfContained=true -p:PublishSingleFile=true -p:EnableCompressionInSingleFile=true
```



You need SDK 8
```
winget install Microsoft.DotNet.SDK.8
```
