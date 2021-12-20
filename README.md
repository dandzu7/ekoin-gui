# Karbo-GUI (Karbo Spring Wallet)

Alt. GUI wallet for [Karbo](https://github.com/Karbovanets/karbo), working with database-driven backend (so-called [Karbo 2](https://github.com/Karbovanets/karbo)). For the version of this wallet based on memory/flat-file-based Karbo core go to https://github.com/seredat/karbo-gui/

**1. Clone wallet sources**

```
git clone https://github.com/Karbovanets/Karbo-GUI.git
```

**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../karbowanec cryptonote
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/Karbovanets/karbo.git cryptonote
```

**3. Build**

```
mkdir build && cd build && cmake .. && make
```

