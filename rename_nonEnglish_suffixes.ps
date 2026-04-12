# Get-ChildItem -Path "C:\Your\Folder\Here" -Recurse -File -Filter "*отредактировано*" | Rename-Item -NewName { $_.Name -replace 'отредактировано','edited' }

param(
    [Parameter(Mandatory=$true)]
    [string]$Folder,

    [Parameter(Mandatory=$true)]
    [string]$oldSuffix,

    [Parameter(Mandatory=$true)]
    [string]$newSuffix
)

Get-ChildItem -Path $Folder -Recurse -File -Filter "*$oldSuffix*" |
    Rename-Item -NewName { $_.Name -replace [Regex]::Escape($oldSuffix), $newSuffix }
