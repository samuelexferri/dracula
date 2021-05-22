# Terminal

Terminal modifications

## Dracula

### Windows Terminal-Powershell

Theme: [Dracula](https://draculatheme.com/)

After official instruction for the color palette, follow this passages:

Install `scoop`:

    Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')

Install `oh-my-posh`:

    scoop install https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/oh-my-posh.json
    Install-Module oh-my-posh -Scope CurrentUser

Move the file `dracula.omp.json` into:

    %USERPROFILE%\Documents\PowerShell\Modules\oh-my-posh\<Version>\Themes

Set the new theme for `oh-my-posh`:

    Set-PoshPrompt -Theme dracula

Move the file `Microsoft.PowerShell_profile.ps1` into:

    %USERPROFILE%\Documents\WindowsPowerShell

In case of errors, run:

    Set-ExecutionPolicity unrestricted
    Unblock-File .\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1

Install `CaskaydiaCove Nerd Font` font family and set in the Windows Terminal settings:

    CaskaydiaCove Nerd Font

### Visual Studio Code

Add `CaskaydiaCove Nerd Font` as font family in the Visual Studio Code settings

## Various

Use Chocolatey, Package Manager for Windows

```bash
choco install <package>
```

Clear history:

```bash
(Get-PSReadlineOption).HistorySavePath
```

## Extensions

### oh-my-posh

[oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh)
