---
layout: page
title: Software
description: Software, který je používaný při vyuce
parent: Zdroje
---

# Software

Instalace SW, který používáme


## Keil uVision

Software, který budeme často využívat je **Keil uVision**. Keil nám umožní programovat a debugovat
mikroprocesory ARM, které budeme používat na hodinách HAW a OPS.

[Stáhnout Keil uVision](https://armkeil.blob.core.windows.net/eval/MDK537.EXE){: .btn .btn-green }
<details class="ml-0">
  <summary>Alternativní způsob stažení</summary>
<div markdown="1">
### Powershell
```powershell
Invoke-WebRequest https://armkeil.blob.core.windows.net/eval/MDK537.EXE -O keil-install-5.3.7.exe
```

### WSL
```bash
curl https://armkeil.blob.core.windows.net/eval/MDK537.EXE -o keil-install-5.3.7.exe
```
</div>
</details>

## Dev-C++

Pro základy programování v jazyce C využijeme starší program, který však bohatě poslouží naším účelům.
Můžete si stáhnout verzi používanou (zatím) ve škole, nebo můžete použít nějakou z alternativ, kterou
je například **Red Panda C++**:

[Red Panda C++](https://sourceforge.net/projects/redpanda-cpp/files/1.2/RedPanda.C%2B%2B.1.2.win64.MinGW-w64.X86_64.GCC.11.2.Setup.exe/download){: .btn .btn-blue }

nebo **Embarcadero Dev-Cpp**:

[Embarcadero Dev-Cpp](https://github.com/Embarcadero/Dev-Cpp/releases/download/v6.3/Embarcadero_Dev-Cpp_6.3_TDM-GCC_9.2_Setup.exe){: .btn .btn-green }
