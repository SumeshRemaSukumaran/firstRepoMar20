pipeline {
 agent any
   stages 
   { 
	 stage('Build')
	 {
		steps
		  {
		    sh "dotnet build 'TestWebApp/TestWebApp.csproj' -c Release -o /app"
          }
     }
	stage('Run')
	{
     steps
	 {
		 sh "dotnet run 'TestWebApp/TestWebApp.csproj'"
     }
    }
  }
}
