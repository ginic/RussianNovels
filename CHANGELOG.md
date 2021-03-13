# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## 2021-03-12
### Fixed
- Fixed hypens showing up as '#' in the following files: Gogol_Taras.txt, Chechov_Dama.txt, Dostoyevsky_Biesy.txt and Dostoyevsky_Idiot.txt

### Changed
- Ran dos2unix to change line endings on the following files: Bulgakov_Master.txt, Bulgakov_TeatralnyjRoman.txt, Chekhov_Dama.txt, Chekhov_Dyadya.txt, Dostoyevsky_Biesy.txt, Dostoyevsky_Idiot.txt, Gogol_Mertvye.txt, Gogol_Taras.txt, Nabokov_Arlekinov_1974_Ilin.txt, Nabokov_Dar_1938.txt, Nabokov_Kamera_1933.txt, Nabokov_Kazn_1936.txt, Nabokov_Korol_1928.txt, Nabokov_Lolita_1955_Nabokov.txt, Nabokov_Mashenka_1926.txt, Nabokov_Nait_1941_Ilin.txt, Nabokov_Otchayanie_1934.txt, Nabokov_Pnin_1957_Ilin.txt, Nabokov_Podvig_1932.txt, Nabokov_Veschi_1972_Ilin.txt, Nabokov_Zashchita_1930.txt, Nabokov_Znakom_1947_Ilin.txt, Pushkin_Pikovaya.txt

### Added
- This changelog
- .gitattributes with auto line ending setting

### Removed
- Nabokov texts by translators other than Ilin: `corpus/Nabokov_Pnin_1957_Barabtarlo.txt`, `corpus/Nabokov_Pnin_1957_Nosik.txt`


## 2021-02-19
### Changed
- Changed `Dostoyevski` to match `Dostoyevsky` in all file names

### Removed
- `corpus/Tolstoi_VoynaIMir_ver1.txt` duplicate version of War and Peace


## 2021-02-07
### Changed
- made all .txt files in corpus non-executible

### Removed
- duplicate of `corpus/Vovchok_ZapiskiPrichyotnika.txt` named `corpus/Vovchok_Zapiski prichyotnika.txt`
