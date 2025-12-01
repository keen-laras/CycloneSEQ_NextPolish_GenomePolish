# NextPolish (Version 1.4.1) Genome Assembly

Hello, everyone!
This is a guide to polish your genome assembly using _NextPolish_

The tutorial is built for [DCS Cloud](https://cloud.stomics.tech/) users

- Github repository: [https://github.com/Nextomics/NextDenovo](https://github.com/Nextomics/NextPolish)
- Contact email for [this](https://github.com/keen-laras/CycloneSEQ_NextPolish_GenomePolish) guide: kinanti.seraphina@gmail.com

## Tutorial
### 1. Image & workflow
Using this image to run software in online/offline task of personal analysis

<img width="1762" height="363" alt="image" src="https://github.com/user-attachments/assets/abc75357-94e4-4548-a49c-817894e6bc4f" />

### 2. Prepare .fofn
#### the directory of all these files below is writen in the .fofn file
Assembled genome (.fa/.fasta) is prepared as input.fofn
NGS short-reads (.fastq) is prepared as sgs.fofn
Raw long-reads (.fastq) is prepared as lgs.fofn

### 3. Upload or use configuration text
Your .fofn files' directory can be directly inputted in the [config.txt](https://github.com/keen-laras/CycloneSEQ_NextPolish_GenomePolish/blob/main/config.txt)

### 4. Run software
`nextPolish config.txt`

Please remember to set the mem and CPU setting in config.txt accordingly!

### 5. Output analysis
