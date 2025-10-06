# Capturing a POS App Screenshot

The POS client is a Windows Forms application. To capture a screenshot you will need a Windows environment with the .NET Framework runtime installed.

1. Open the solution `pos.sln` in Visual Studio on Windows.
2. Configure the database connection so that it points to your local copy of `db/pos.mdf`.
3. Press **F5** (or click **Start**) to launch the application.
4. Navigate to the screen or workflow you would like to capture.
5. Use the Windows Snipping Tool (or **Win+Shift+S**) to capture the desired area.
6. Save the screenshot as a PNG file and add it to the repository under `Resources/` or another documentation folder.

> **Note:** The headless Linux CI environment that powers this repository cannot launch the WinForms UI, so screenshots must be captured manually on a Windows workstation.
