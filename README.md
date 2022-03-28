# Ejercicio-3

Primitive Data Type
Task 1
Use “Get-Help” to find out more information about 5
cmdlets.
As an example you can use “Get-Service” or “Out-GridView”
Notes:
Get-Help Get-Help

![image](https://user-images.githubusercontent.com/91616284/160491030-2c32995b-de3f-4f5b-9e43-46e190c0ce85.png)


Get-Help New-Item

![image](https://user-images.githubusercontent.com/91616284/160491130-54f412d2-dacb-4d8a-8002-618f7ffd1d97.png)


Get-Help Get-Alias

![image](https://user-images.githubusercontent.com/91616284/160491241-3de9fa8e-8272-4615-8d6d-6a19ae06e302.png)


Get-Help Get-AuthenticodeSignature

![image](https://user-images.githubusercontent.com/91616284/160491346-4a624dc5-fb5d-4efb-9490-cd37dfd523cf.png)


Get-Help Get-ControlPanelItem

![image](https://user-images.githubusercontent.com/91616284/160491411-da93b20b-c792-4964-b604-3ba9a01abb41.png)


# Although any 5 cmdlets will do


Task 2
Use “Get-Help” with the “–Example” parameter for the
5 cmdlets you discovered more about in task 1.
Notes:

Get-Help Get-Help -Examples

![image](https://user-images.githubusercontent.com/91616284/160491614-7cfada4c-4824-4018-b238-d270bb33fc5c.png)


Get-Help New-Item -Examples

![image](https://user-images.githubusercontent.com/91616284/160491730-7cea06b0-e8fc-47d3-9e8b-394627f33934.png)


Get-Help Get-Alias -Examples

![image](https://user-images.githubusercontent.com/91616284/160491858-8b82661d-c33b-45ef-bbee-886ea63d490d.png)


Get-Help Get-AuthenticodeSignature -Examples

![image](https://user-images.githubusercontent.com/91616284/160491991-b9ac5c71-2338-4fe9-92ab-cb4cf72a1aed.png)


Get-Help Get-ControlPanelItem -Examples

![image](https://user-images.githubusercontent.com/91616284/160492056-d6e1a539-2b06-4097-855f-5cb845ca6319.png)


# Although any 5 cmdlets will do

Task 3
Create a new text file named “TestFile.txt” under C:\
Maximo\PowerShell\Workshop1\%USERNAME%
The cmdlet to make a file and a new directory starts with “New”
Notes:

New-Item -Path C:\ -Name Expo -ItemType Directory

![image](https://user-images.githubusercontent.com/91616284/160492310-4806f52e-0c58-442d-a79e-7b2a2a96b16d.png)


New-Item -Path C:\Sudoblark -Name PowerShell -ItemType Directory

![image](https://user-images.githubusercontent.com/91616284/160492670-4d80c181-e32c-46d2-aa20-794c336a7bf6.png)


New-Item -Path C:\Sudoblark\PowerShell -Name Workshop1 -ItemType Directory

![image](https://user-images.githubusercontent.com/91616284/160492828-ab3259e5-99f4-4ab7-a95e-193abb44b780.png)


New-Item -Path C:\Sudoblark\PowerShell\Workshop1 -Name bclark -ItemType Directory

![image](https://user-images.githubusercontent.com/91616284/160492970-fd1c59f3-07a2-4231-890e-314f75df10d5.png)


New-Item -Path C:\Sudoblark\PowerShell\Workshop1\bclark\ -Name Testfile.txt -ItemType 
File

![image](https://user-images.githubusercontent.com/91616284/160493094-e89ac3e5-b203-4665-803c-1a03ef50d345.png)


Task 4
Populate the text file you created in task 3 with all
three datatypes we’ve covered: “Boolean”, “String”
and “Int”
The cmdlet you need starts with “Add”
Notes:

Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value True

![image](https://user-images.githubusercontent.com/91616284/160493420-4286d3c2-8434-4c30-87cf-49566774f151.png)


Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value "Hello"

![image](https://user-images.githubusercontent.com/91616284/160493487-172491e7-ab00-4538-bfba-763d5f7fb156.png)


Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value 42

![image](https://user-images.githubusercontent.com/91616284/160493567-93948ee7-0bcb-4133-95d4-0f60b769822c.png)


Task 5
Read from the text file and use “Get-Member” to find
the datatype returned
The cmdlet you need to read data from the text file begins to “Get”
Notes:

Get-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt | Get-Member

![image](https://user-images.githubusercontent.com/91616284/160493692-c24f3db1-ddaf-4ff4-83f2-8c7a45cbcf38.png)


Task 6
Overwrite all data within the text file that you created
in task 3.
The cmdlet you need starts with “Set”
Notes:
Set-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value "Boooooo"

![image](https://user-images.githubusercontent.com/91616284/160493903-1acbdaba-6068-4b6a-a12c-fae1fda24173.png)


Task 7
Format the data returned by a cmdlet into a list
You will need to pipe the original cmdlet then use the “Format-List”
cmdlet
Notes:
Get-Service | Format-List

![image](https://user-images.githubusercontent.com/91616284/160494102-501f4edb-a407-4d8a-896f-77c9ead42f73.png)


Task 8
Pipe “Get-Command” into “Out-GridView”
Notes:
Get-Command | Out-GridView

![image](https://user-images.githubusercontent.com/91616284/160494323-351b2b21-4141-4f15-8c03-32751da9715a.png)


Task 9
Pipe the 5 cmdlets you discovered in task 1 into “Out-
GridView”

Notes:
Get-Help | Out-GridView

![image](https://user-images.githubusercontent.com/91616284/160494498-f9657c98-9885-4682-bebf-87502b8bc9cf.png)


New-Item | Out-GridView

![image](https://user-images.githubusercontent.com/91616284/160494575-51e98739-75b5-411a-9752-a892741029da.png)

![image](https://user-images.githubusercontent.com/91616284/160494654-98e33ca3-472e-4285-9cb0-eff791a3ff91.png)


Get-Alias | Out-GridView

![image](https://user-images.githubusercontent.com/91616284/160494871-b7faae6f-fd96-403f-8c49-72411a24047b.png)


Get-AuthenticodeSignature | Out-GridView

![image](https://user-images.githubusercontent.com/91616284/160494987-7f540ad6-e83e-4e9a-a201-18fb7787daa6.png)


Get-ControlPanelItem | Out-GridView

![image](https://user-images.githubusercontent.com/91616284/160495069-d5ab589b-9de1-4a10-b89e-7a016f59d23b.png)


Task 10
Find the official PowerShell documentation library from
Microsoft
Google MSDN PowerShell. The URL starts with
“https://docs.microsoft.com”
