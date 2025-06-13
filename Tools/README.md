# 🛠️ Parrot “Tools” Workspace

This directory is a **git-clonable grab-bag of open-source hacking, DFIR, and CTF utilities**.  
Every sub-folder below is a full upstream project (or binary) checked out locally so you can work offline, hack on code, or pin to a known version for reproducible labs.

> **How to replicate from scratch**

```bash
# 1. Create a fresh folder and cd in
mkdir -p ~/Desktop/Tools && cd $_

# 2. One-liner to clone everything listed in this README
while read repo dir; do
  git clone --depth 1 "$repo" "$dir"
done <<'EOF'
https://github.com/jivoi/awesome-osint                 awesome-osint
https://github.com/Yara-Rules/rules                    awesome-yara
https://github.com/ReFirmLabs/binwalk                 binwalk
https://github.com/digininja/CeWL                      CeWL
https://github.com/ivan-sincek/chankro                 Chankro
https://github.com/securisec/chepy                    chepyForx
https://github.com/0xdea/chess-encryption             chessencryption
https://github.com/0xdea/chess-steg-cli               chess-steg-cli
https://github.com/jesseduffield/lazygit              cli
https://github.com/codeigniter4/CodeIgniter4           CodeIgniter4
https://github.com/pandasec888/convoC2                 convoC2
https://github.com/NullArray/Crack-A-Mauz              Crack-A-Mauz
https://github.com/cryptii/cryptii                     cryptii
https://github.com/zardus/ctf-tools                    CTF-Tools
https://github.com/rs/curlie                           curlie
https://github.com/enaqx/cybersecurity-list            cybersecurity
https://github.com/DAO-DAO-Project/dao-dao             dao-dao-ui
https://sqlitebrowser.org/dl/                          DB.Browser.for.SQLite-v3.13.1-x86.64-v2.AppImage
https://github.com/Paradoxis/Decrypt                   decryptStuff
https://github.com/IDerr/DeepSeek-V3                   DeepSeek-V3
https://github.com/horsicq/Detect-It-Easy              Detect-It-Easy
https://github.com/snyk/driftctl                       driftctl
https://github.com/kgretzky/evilginx2                  evilginx2
https://github.com/mandiant/flare-vm                   flare-vm
https://github.com/OJ/gobuster                         gobuster
https://github.com/codex-team/graphcat                 graphcat
https://github.com/haiticoders/haiti                   haiti
https://github.com/hashcat/hashcat                     hashcat
https://github.com/psypersky/hashID                    hashID
https://github.com/honojs/session                      hono_sessions
https://github.com/exiftool/exiftool                   Image-ExifTool-13.30
https://github.com/injection-payloads/injection-payload-list InjectionPayloadList
https://github.com/n0x00/jailbreak                     jailbreak
https://github.com/openwall/jumbo                      jumboJohn
https://github.com/laravel/laravel                     laravel
https://github.com/ax0ne/Legacy-iOS-Kit                Legacy-iOS-Kit
https://github.com/soxoj/maigret                        mcp-maigret
https://github.com/MOAB-Mentalist/mentalist            mentalist
https://github.com/rapid7/metasploit-framework         metasploit-framework
https://github.com/eclipse/mosquitto                   mosquitto
https://github.com/NCAE-CyberGames/Prep-Guides         NCAE_CyberGames_Prep
https://github.com/sambowden/NTHW                      NTHW
https://github.com/owasp-amass/ocd-mindmaps            ocd-mindmaps
https://github.com/OneRuleToRuleThemAll/OneRule        OneRuleToRuleThemStill
https://github.com/OpenCTI-Platform/opencti            opencti
https://github.com/swisskyrepo/PayloadsAllTheThings    PayloadsAllTheThings
https://github.com/carlospolop/PEASS-ng                PEASS-ng
https://github.com/itm4n/PrivescCheck                  PrivescCheck
https://github.com/berzerk0/Probable-Wordlists         Probable-Wordlists
https://github.com/pwndbg/pwndbg                       pwndbg
https://github.com/tejainece/RecursiveExtractor        RecursiveExtractor
https://github.com/moloch--/RootTheBox                 RootTheBox
https://github.com/ius/rsatool                         rsatool
https://github.com/danielmiessler/SecLists             SecLists
https://github.com/mdefune/SilkRoad                    SilkRoad
https://github.com/zardus/ctf-steganography            steganography
https://github.com/super/general                       super
https://github.com/vanhauser-thc/thc-hydra             thc-hydra
https://github.com/laramies/theHarvester               theHarvester
https://github.com/tnok/cipher.knock                   tnok
https://github.com/danielmiessler/word-reaper          word-reaper
https://github.com/zod-lal-lab/zods-llm-web-scrapper   zods-llm-web-scrapper
