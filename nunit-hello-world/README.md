#NUnit.Examples - This will be the library project

#NUnit.Examples.test - Here we will write NUnit test cases

#Go to Nuget and download following project 

#1 NUnit (enable the project to create and run nunit test cases)

#2 Run NUnit from Visual Studio 

	# Download NUnit3TestAdapter package from Nuget
	# Go to Test => Windows => Test Explorer and you will see all test cases in left side of visualstudio


#3 Run nunit from nunit console 

    # Download NUnit.ConsoleRunner package from Nuget (to run from console)
	# Go to the Nunit console package in unit package folder 
	# C:\D-Drive\Code\Visual-Studio\UnitTestExamples\NUnitTest.Examples\packages\NUnit.ConsoleRunner.3.6.1\tools>
	# Run the test cases as follows 
    # C:\D-Drive\Code\Visual-Studio\UnitTestExamples\NUnitTest.Examples\packages\NUnit.ConsoleRunner.3.6.1\tools>nunit3-console.exe C:\D-Drive\Code\Visual-Studio\UnitTestExamples\NUnitTest.Examples\NUnitExamples.Tests\bin\Debug\Calculator.Test.dll

