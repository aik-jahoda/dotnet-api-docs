all: service.exe client.exe
 
service.exe: service.vb Snippets.vb
 vbc /t:exe service.vb Snippets.vb /r:System.ServiceModel.dll /libpath:c:\whidbey\assemblies
 
client.exe: client.vb 
 vbc /t:exe client.vb /r:System.ServiceModel.dll  /libpath:c:\whidbey\assemblies
