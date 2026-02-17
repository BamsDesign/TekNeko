# Apendiks pou Diskloz Itilizasyon AI

**Non Etidyan an** Ovide Hans-Omar Harold (Jean Baptiste-woodley, Barthelemy Andji-Michael)
**Tit Pwojè a:** SunTracker
**Dat:** 16/02/2026 

---

## Enstriksyon
**Konplete apendiks sa si w itilize zouti Entèlijans Ayifisyèl nan pwojè ou a. Li te mèt te kòd, rechèch ki gen asistans AI, chatbot, oubyen nenpòt lòt zouti AI, ou dwe soumèt pwojè ou a ak dokiman sa.**

**Si w pat itilize zouti AI, Tcheke sa** 

☐ *Pa gen zouti AI ki te itilize pou travay sa*

---

## Istorik Itilizasyon Zouti AI

**Konplete yon seksyon pou chak zouti AI/Sesyon ou itilize:**

### Zouti AI #1

**Non/Platfòm Zouti a:** ChatGPT  
*(ekz., ChatGPT, Grammarly, GitHub Copilot, Rechèch Google, elatriyeee.)*

**Dat & Lè Itilizasyon an:** 14/022026

**Objektif Itilizasyon an:** Asistans rechèch
*(Ekz., Deboge kòd, Asistans rechèch, elatriyee.)*

**_Prompt_ oubyen Rekèt ki te fèt la**
```
[Kopye/Kole ekzakteman tèks ou te tape nan zouti AI a]
1- Kijan poum mete logo pou Flutter app?
2- Eske API a retounen lè an ki timezone?
  Kijan nou konvèti lè a pou itilizatè a?
  Si m vle wè lè Japon pandan m Ayiti, sa k ap pase?




```

**Tout repons/output zouti AI a te bay la:**
```
[Kopye/Kole ekzakteman repons (san modifikasyon) ou jwenn nan men zouti AI a]

1- Pou mete logo pou yon Flutter app:

Mete logo a nan assets/images/

Ajoute li nan pubspec.yaml

Oswa itilize package flutter_launcher_icons

Konfigire:

dev_dependencies:
  flutter_launcher_icons: ^0.13.1

flutter_launcher_icons:
  android: true
  ios: false
  image_path: "assets/images/logo.png"

  2- 2026-02-16T11:15:22+00:00

  
  3- Nou itilize:

DateTime.parse(iso).toLocal();


Fonksyon konvèsyon:

String formatIsoToLocalHHmm(String iso) {
  try {
    final dt = DateTime.parse(iso).toLocal();
    final hh = dt.hour.toString().padLeft(2, '0');
    final mm = dt.minute.toString().padLeft(2, '0');
    return '$hh:$mm';
  } catch (_) {
    return iso;
  }
}


Sa konvèti UTC → Lè lokal aparèy la.



```

**Kòman w te itilize repons ou te jwenn nan:**  
*(Dekri etap pa etap sa w te fè ak kontni zouti AI sa te jenere a)*
```
[Ekzanp: "Mwen itilize kòd AI a ban mwen depi nan kòmansman, aprè mwen modifye non varyab yo pou li ka koresponn ak pwojè mwen an epi mwen teste li."]
Mwen te itilize kòd AI a te ban mwen pou m mete konvèsyon lè UTC pou li tounen lè lokal itilizatè a. Apre sa mwen modifye kèk pati nan kòd la pou li adapte ak pwojè mwen an, epi mwen teste aplikasyon an sou telefòn pou verifye li mache byen. Mwen te itilize AI tou pou ede m konprann kestyon timezone ak mete logo nan aplikasyon an.



```

**Kisa w aprann sou repons ou jwenn nan?**  
*(Kisa w aprann sou pwosès la? Kòman zouti AI sa ede w nan aprantisaj ak konpreyansyon w?)*
```
Mwen aprann API a bay lè yo an UTC, epi pou montre lè a kòrèk pou itilizatè a, mwen dwe konvèti li an lè lokal (timezone telefòn nan). Mwen aprann tou si mwen vle wè lè yon lòt peyi (tankou Japon), mwen bezwen chwazi timezone peyi a oswa sèvi ak yon metòd ki konvèti lè a pou timezone sa. Zouti AI a ede m konprann diferans UTC vs lè lokal, epi li gide m nan fason pou m aplike konvèsyon an nan kòd Flutter la.

```

## Kontribisyon Sou Travay Final La

**Pousantaj kontribisyon pa w antanke imen, sou travay final la:** 70%

------

### Zouti AI #2
_Rekopye menm seksyon anlè a, si gen lòt zouti_

---



---
<img width="203" height="104" alt="image" src="https://gist.github.com/user-attachments/assets/a979028b-66f8-4661-83fc-b22b41e0eb3b" />

## Rekonesans Entegrite Akadamik ESIH

Soumèt apendiks sa vle di ke mwen afime ke:
- [OK] Mwen bay verite epi diskloz tout zouti AI mwen itilize pou pwojè sa
- [ ] _Prompt_ ak rekèt mwen bay yo konplè epi ekzat
- [ ] Mwen konprann si mwen pa diskloz tout zouti AI yo, sa ka kontribiye ak dezonè plis echèk mwen nan matyè sa

**Siyati Etidyan** Ovide Hans Omar Harold
**Dat:** 16/02/26

---
