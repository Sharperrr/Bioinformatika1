# Bioinformatika1 2110581 Simas Krikščiūnas 5 grupė 

Atstumo funkcija skaičiuota euclidean metodu

Formulė atstumo tarp dviejų vektorių (pavyzdžiui, tarp dviejų virusų ar rūšių) skaičiavimui yra:
![image](https://github.com/user-attachments/assets/ce82b66f-a136-40cb-b21a-a69a266f4f12)

kur 𝑓𝑖𝑘 ir 𝑓𝑗𝑘 – tai k-tojo kodono/dikodono dažnis atitinkamuose virusuose/rūšyse i ir j. Tai leidžia gauti atstumo matricas, kurios vėliau naudojamos dendrogramų sudarymui, parodant genetinius ar evoliucinius skirtumus.

Naudojant gautus kodonų dažnius, buvo suformuoti hierarchiniai dendrogramos medžiai, kurie parodo, kaip skirtingos bakterijų ir žinduolių grupės klasterizuojasi pagal jų kodonų dažnius. Žemiau pateikta dendrograma yra suformuota naudojant aminorūgščių dažnių klasterizaciją.

![image](https://github.com/user-attachments/assets/6c2f2be0-446d-43fe-bdf8-093165e1b541)

Iš dendrogramos matyti, kad yra dvi pagrindinės grupės:

- Viena grupė sudaryta iš bacterial2, mamalian2, mamalian4.
- Kita grupė apima likusias rūšis: bacterial1, bacterial3, bacterial4, mamalian1, mamalian3.

Analizuojant kodonų ir dikodonų dažnius, pastebimas skirtumas tarp bakterijų ir žinduolių virusų. Bacterial2 ir mamalian2 pasirodė esantys gana panašūs, tačiau bendrame vaizde klasterizavimas parodė, kad žinduolių ir bakterijų virusai sudaro atskiras grupes.
**
Išskirtinumai:**
- bacterial2 ir mamalian2 yra išskirtiniai, nes jų atstumas tarpusavyje yra sąlyginai mažas. Šios rūšys pasirodo esančios genetiniu požiūriu artimesnės nei kiti bakterijų ir žinduolių virusai.
- labiausiai variavo bacterial4 ir mamalian3, kurių atstumas iki kitų virusų buvo didžiausias, rodant, kad jų kodonų ar dikodonų dažniai smarkiai skiriasi nuo kitų virusų. Šie skirtumai galėjo lemti didesnius genetinius nuokrypius.
