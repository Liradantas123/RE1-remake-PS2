**Revil1 – PS2 Port GameCube RE1 Remake**

Revil1  – PS2 port GC RE1 remake Fan-made project to port Resident Evil (2002)
from GameCube to PlayStation 2, preserving the original experience.
I'm not experienced in game development, but I'm passionate about this
project and willing to contribute, learn, and help in any way I can.

**Revil1 – PS2 Port GameCube RE1 Remake**

Projeto feito por fãs para portar Resident Evil (2002),
originalmente lançado para GameCube, para o PlayStation 2,
preservando a experiência original.
Não tenho experiência em desenvolvimento de jogos,
mas sou apaixonado por este projeto e estou disposto a contribuir,
aprender e ajudar da maneira que puder.

STEP-BY-STEP

1. MAPPING AND RECONSTRUCTION
├── Assets (Textures, Audio, Models, Videos) -> Convert to PS2-compatible formats
└── Binary (.dol) -> Decompile via REA + Ghidra -> Readable C/C++ source code

2. CODE ADAPTATION (Porting Layer)
├── Game Logic (Physics, AI, Mechanics) --------> Keep intact in C/C++
└── Hardware Layer (GX Graphics, Audio) ---------> Rewrite using PS2SDK (GS/SPU2)

3. COMPILATION AND TESTING
└── Final C/C++ Code ---> MIPS Compiler (GCC) ---> PS2 Executable (.ELF)

Passo a Passo

1. MAPEAMENTO E RECONSTRUÇÃO
├── Assets (Texturas, Áudio, Modelos, VÍdeos) -> Converter para formatos do PS2
└── Binário (.dol) -> Descompilar via REA + Ghidra -> Código-fonte C/C++ legível

2. ADAPTAÇÃO DO CÓDIGO (Porting Layer)
├── Lógica do Jogo (Física, IA, Regras) --------> Mantém intacta em C/C++
└── Camada de Hardware (Gráficos GX, Áudio) -----> Reescreve usando PS2SDK (GS/SPU2)

3. COMPILAÇÃO E TESTE
└── Código Final C/C++ ---> Compilador MIPS (GCC) ---> Executivo PS2 (.ELF)
