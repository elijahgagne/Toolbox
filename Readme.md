
---------------------------------------------------------------------------
-- UI
---------------------------------------------------------------------------

Main tab
- Search

Settings
- Button off of main tab

New tab
- Close button
- Inputs
- Build
- Run



---------------------------------------------------------------------------
-- Tool file
---------------------------------------------------------------------------

Sections:
1) Metadata
2) Interpreter
3) Inputs
4) Outputs

Metadata
- Name
- Description
- Keywords
- Author
- Date


Interpreter
- PowerShell
- Bash
- Python
- Node
- Perl
- C#

Inputs
- TextBox
- Multiline TextBox
- CheckBox
- ComboBox
- Credential

Outputs
- Build
- Text
- Grid



<tool>
  <metadata>
    <name></name>
	<description></description>
	<keywords></keywords>
	<author></author>
	<date></date>
  </metadata>
  <interpreter name="PowerShell" />
  <inputs>
    <text displayname="First Name" scriptname="$firstName" />
	<text displayname="Last Name" scriptname="$lastName" />
  </inputs>
  <outputs types="Build,Text,Grid" />
  <script>
    <![CDATA[
	
Hello $firstName $lastName!
	
    ]]>
  </script>
</tool>











