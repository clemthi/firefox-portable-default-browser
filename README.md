# Register Firefox Portable as default browser

The following Windows registry keys allow you to register an instance of Firefox Portable as your default browser.

## Keys

Create registry keys are located under:

- `HKEY_CURRENT_USER\Software\Classes\FirefoxPHTML`
- `HKEY_CURRENT_USER\Software\Classes\FirefoxPPDF`
- `HKEY_CURRENT_USER\Software\Classes\FirefoxPURL`
- `HKEY_CURRENT_USER\Software\Clients\StartMenuInternet\Firefox Portable`
- `HKEY_CURRENT_USER\Software\RegisteredApplications` (key named `Firefox Portable`)

## Usage

To execute the registry you need to :

- Edit the script by setting the path to your executable (by default `c:\\path\\to\\firefox-portable.exe`)
- Import the keys in your registry (by double-clicking the file or importing them using `regedit`).

Et voilà.
