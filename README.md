# 📚 Maturitetni zapiski — skupni vault

Dobrodošel/-a! Ta vault je skupen prostor za deljenje zapiskov pred maturo. Vsak dela na **svojem branchu**, da ne gnjavite drug drugega.

> **Potrebuješ plugin:** [Obsidian Git](https://obsidian.md/plugins?id=obsidian-git) — namesti ga v Settings → Community plugins.  
> Command palette odpreš z `Ctrl+P` (Windows/Linux) ali `Cmd+P` (Mac).

---

## 🚀 Začetek — prvič

### 1. Ustvari mapo in kloniraj repozitorij

Kjer hočeš imeti vault (npr. Dokumenti), **ustvari novo mapo** — poimenuj jo npr. `matura-vault`.

Desni klik na mapo → **Odpri v terminalu** in zaženi:

```
git clone https://github.com/David7bre/matura-vault.git .
```

> Pika na koncu je pomembna — klonira vsebino direktno v to mapo, ne v podmapo.

---

### 2. Odpri vault v Obsidianu

Zaženi Obsidian → **Open folder as vault** → izberi mapo ki si jo ustvaril/-a.

Ob prvem odprtju te vpraša za zaupanje pluginom — klikni **Trust and enable**.

---

### 3. Ustvari svoj branch

```
Obsidian Git: Create new branch
```

Poimenuj ga `<tvoje-ime>`, npr. `ana`.  
Plugin te bo samodejno preklopil na novi branch.

---

### 4. Potisni branch na GitHub

```
Obsidian Git: Push
```

Ob prvem pushu te bo vprašal za GitHub prijavo — sledi navodilom. ✅

---

## ✏️ Vsakdanje delo

Vault se **samodejno komita in potisne na GitHub vsakih 10 minut** — ni ti treba delati ničesar.

Če hočeš takoj shraniti in sinhronizirati:

```
Obsidian Git: Commit and sync
```

To naredi commit + pull + push v enem koraku.

---

## 🔀 Preklapljanje med branchevi

> ⚠️ Preden preklopiš, naredi `Commit and sync` — sicer boš izgubil/-a neshranjene spremembe.

**Če branch že imaš lokalno** (npr. tvoj lastni):

```
Obsidian Git: Switch branch
```

Izberi branch iz seznama.

**Če branch še nimaš lokalno** (npr. sošolčev, ki ga vidiš prvič):

```
Obsidian Git: Switch to remote branch
```

Izberi `origin`, nato izberi branch (npr. `ana`). To ustvari lokalni branch in te preklopi nanj — od zdaj naprej ga najdeš v navadnem `Switch branch`.

---

## 📥 Uvoz zapiskov od drugega

1. Preklopi na sošolčev branch — če ga še nimaš lokalno:
    
    ```
    Obsidian Git: Switch to remote branch
    ```
    
    → izberi `origin`, nato `<sošolec>`. Naslednjič ga najdeš kar v navadnem `Switch branch`.
    
2. Najdi datoteko v levem file explorerju in jo **kopiraj** (desni klik → Copy).
    
3. Vrni se na svoj branch:
    
    ```
    Obsidian Git: Switch branch
    ```
    
    → izberi `<tvoje-ime>`
    
4. Prilepi datoteko in počakaj na avtomatski commit ali ročno:
    
    ```
    Obsidian Git: Commit and sync
    ```
    

---

## 📁 Priporočena struktura map

```
📁 matura-vault/
├── 📁 slovenščina/
├── ... (dodaj po potrebi)
└── README.md  ← ta datoteka
```

---

## ❓ Pogoste težave

**Push zavrne s `rejected`:**

```
Obsidian Git: Pull
```

Nato poskusi push znova.

**Nisi prepričan/-a na katerem branchu si:**  
Poglej v spodnji statusni bar Obsidiana — ime brancha je prikazano tam (npr. `ana`).

**Hočeš videti zgodovino commitov:**

```
Obsidian Git: Open source control view
```

---

## 👥 Branci

|Ime|Branch|
|---|---|
|_(dodaj sebe sem ko se pridružiš)_|`<ime>`|

---

_Vprašanja? Odpri Issue na GitHubu ali piši v skupino._ 🤙