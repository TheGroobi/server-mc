### ZeroTier

1. Pobierasz [ZeroTier](https://www.zerotier.com/download/) i odpalasz
2. Tutaj otwierasz odpalone programy
![[Pasted image 20240912133358.png]]

3. Klikasz Prawym na ikonkę i join network 
![[Pasted image 20240912133445.png]]
Wpisujesz tam ten dziwny kodzik 15 znaków co wysłałem pv bo nie można zleakować i działa

### Jak pobrać modpack (dla opornych) 
#### - Wersja dla oponentów z premium minecraft
1. Pobierasz [CurseForge](https://www.curseforge.com/download/app)
2. Wyszukujesz w minecraft "Better MC  [FORGE] - BMC4" 
   ![[Pasted image 20240912134017.png]]
3. GIGA WAŻNE, zanim pobierzecie musicie zmienić wersje modpack'a na 30.5![[Pasted image 20240912134153.png]]![[Pasted image 20240912134206.png]]
   
   4. Modpack pobrany można kliknąć Play pozdrawiam serdecznie, w następnym tutorialu pomogę wam zmienić ram żeby minicraft działał jak powinien. [Tutaj se kliknij](#Jak Zmienić Ram w minikraft)

#### - Wersja dla biedniejszych z minecraft nie premium

Nie wiem nie chce mi się patrzeć jak to się robi pozdrawiam.

### Jak zmienić ram w minikraft (też minikraft premium)

Jak już odpalicie swój launcher minecraft:
- Instalacje 
  ![[Pasted image 20240912134721.png]]
- Trzy kropeczki > Edit ![[Pasted image 20240912134804.png]]
- Więcej opcji 
  ![[Pasted image 20240912134827.png]]
- Zmieniamy pierwszy argument w JVM ARGUMENTS
  ![[Pasted image 20240912134858.png]]
  
  Najlepiej zrobić to na połowe ramu jaki macie w kompie, jeśli nie wiecie ile macie to dajcie 6g
  
  przykład w moim kompie co ma 16gb ramu daje połowe:
  `-Xmx4069m` -> `-Xmx8g`
  ![[Pasted image 20240912135021.png]]
  
  Ciekawostka można to też zrobić z poziomu CurseForge i nie trzeba tego zmieniać co odpalenie klienta kloców

- Trzy kropki > Profile Options
  ![[Pasted image 20240912135213.png]]
  - Odznaczacie Memory Settings 
![[Pasted image 20240912135232.png]]
- i ustawiacie ile chcecie (1GB = 1024MB) Dla Leniwych [link](https://www.gbmb.org/gb-to-mb)