

pipeline {
 agent any
   stages 
   { 
	 stage('Build')
	 {
		steps
		  {
		  echo 'hello'
           // sh "dotnet build 'TestWebApp/TestWebApp.csproj' -c Release -o /app"
          }
     }
	stage('Run')
	{
     steps
	 {
	 echo 'hello1'
         // sh "dotnet run 'TestWebApp/TestWebApp.csproj'"
     }
    }
  }
}
