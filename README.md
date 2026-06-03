# TrocMarket 🔄

> "Troque, vends, donne — parce qu'au Cameroun, rien ne se perd, tout s'échange."

## Structure
```
trocmarket/
├── mobile/    → Expo React Native (TypeScript)
└── backend/   → Spring Boot 3 + MySQL
```

## Démarrage rapide

### Backend
```bash
cd backend && ./mvnw spring-boot:run
```

### Mobile
```bash
cd mobile && npm install && npx expo start
```
🗺️ MAPPING MAQUETTES → FICHIERS

1) 1app/index.tsxSplash screen ✅ 
2) 2,3,4(auth)/onboarding.tsx3 slides Troc/Don/Vente ✅ 
3) 5(1),5(2)(auth)/inscription.tsxPage auth unique (scroll)✅
4) 6(auth)/connexion.tsxOTP Connexion ✅
5) 7,8,9(auth)/zone.tsxSélecteur zone (Campus/Quartiers/Villes)✅
6) 10(tabs)/accueil.tsxLe Marché ✅
7) 11(1),11(2),11(3)(tabs)/explorer.tsxFiltres avancés (scroll)✅
8) 12(1),12(2),12(3)annonce/[id].tsxDétail annonce (scroll)✅
9) 13(1)→13(4)vendeur/[id].tsxProfil vendeur (tabs)✅
10) 14(1)→14(5)publier/index.tsxPublication (scroll unique) ✅
11) 15(1)→15(5)publier/mode.tsxChoix type (Troc/Don/Vente) ✅
12) 16(1)→16(3)proposition/[id].tsxProposer un troc ✅
17) 21(1),21(2)mes-objets/index.tsxGestion annonces ✅
18) 22(1)→22(4)portefeuille/index.tsxWallet + modals ✅
20) 24(1)→24(7)(tabs)/profil.tsxProfil + Paramètres + modals ✅
21) 25carte/index.tsxCarte géo ✅
13) 17(1),17(2)(tabs)/messages.tsxListe discussions 
14) 18(1)→18(4)chat/[id].tsxFenêtre chat 
15) 19(1)→19(3)confirmation/[id].tsxQR Code + Code secret
16) 20(1)→20(3)notation/[id].tsxNotation feedback
19) 23(1),23(2)paiement/[id].tsxPaiement Mobile Money ✅