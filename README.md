# Sales - Java Mobile Project (2005)

> **Note:** This repository contains the original version in Portuguese (file names, variables, and methods).  You will soon find the repository that contains the English-translated version here: [java SuperWaba 2005 en](https://github.com/celsomsilva/java-mobile-2005-en).


This is a legacy project developed in 2005 using **Java** and the **SuperWaba** SDK — a mobile development platform derived from the **Waba project**, an early pioneer in mobile Java development (before Java ME).

This commercial application, `Sales`, was built for mobile devices running **Palm OS** (eg: Zire, Tungsten, Sony Clie) and **Windows CE** platforms.

---

## About SuperWaba

The SuperWaba company — led by **Guilherme Campos Hazan** — continued the original Waba Project, which began in 1999, and was later incubated at the **Pontifical Catholic University of Rio de Janeiro (PUC-Rio)**.

SuperWaba SDK initially supported Palm OS devices and later expanded to Windows CE and other platforms via SDL from version 5.0. It was a popular option for enterprise mobile applications throughout the early 2000s. SuperWaba was officially adopted in large-scale projects in Brazil.

> **Note:** SuperWaba was later renamed and evolved into [TotalCross](https://github.com/TotalCross/totalcross), a modern, lightweight mobile SDK offering improved performance and broader cross-platform support.

---

## About This Project

The Sales application and examples included in the SuperWaba package were developed in 2005 by me while working at SuperWaba.

The goal was to create a portable, lightweight, and efficient mobile sales force management system for handheld devices used by sales teams in the field.

**Main functionalities:**
- Client management  
- Product catalog management  
- Price table handling  
- Order entry and tracking  
- Sales reporting and dashboards  


---

## Project Structure


> At that time, Java packages typically followed simple directory-based naming (e.g., `bd/`, `ui/`, `cliente/`)  
> instead of domain-based structures (`br.com.project...`).  
> This reflects the early pre-Eclipse Java era.



```
java-mobile-2005/
  sales/
    bd/
      ClienteBD.java
      ItemDoPedidoBD.java
      ParametrosBD.java
      PedidoBD.java
      ProdutoBD.java
      TabelaDePrecoBD.java

    ui/
      cliente/
        ClienteCreditos.java
        ClienteEnderecoDeCobranca.java
        ClienteEnderecoDeEntrega.java
        ClienteEndereco.java
        ClienteGeral.java
        ClienteMaisEndereco.java
        ClienteMaisInfo.java
        ClientesMenu.java
        NovoCliente.java
        ProcuraClientes.java

      produto/
        NovoProduto.java
        ProcuraProdutos.java
        ProdutosMenu.java

      pedido/
        ItemsDoPedido.java
        NovoPedido.java
        PedidoGeral.java
        PedidoTabelaDePreco.java
        PedidosMenu.java
        ProcuraPedidos.java

      relatorios/
        RelatorioMenu.java

        sumariodevendas/
          Anual.java
          Diario.java
          Mensal.java
          PorPeriodo.java
          SumarioDeVendasMenu.java

        vendasporproduto/
          Anual2.java
          Diario2.java
          Mensal2.java
          PorPeriodo2.java
          VendasPorProdutoMenu.java

      BaseMenu.java
      MenuPrincipal.java

    DynamicTabPanel.java
    ForcaDeVendas.java
```

---

> **Note on code comments:**  
> The original source files preserve their historical form.  
> Comments appear in both **Portuguese** and **English**, reflecting the original 2005 code style — written manually, without automated translation tools.


## Institutional Use

SuperWaba was officially adopted in large-scale projects in Brazil, including government-led initiatives. Notably:

In **2009**, the **Brazilian Ministry of Planning, Budget and Management**, through the **IBGE (Brazilian Institute of Geography and Statistics)**, issued an official tender for the **migration of the Censo 2010 mobile application from SuperWaba to TotalCross**.

**Official Tender Highlights:**
- **Tender:** Pregão Eletrônico Nº 76/2009  
- **Service:** Migration of Censo2010 mobile application from SuperWaba to TotalCross  
- **Included Deliverables:**
  - Full code review and optimization for TotalCross
  - Workshop to train a 15-person internal IBGE team on TotalCross technology and source code updates
  - Licensing of **260,000 virtual machines** for a one-year period

**Source:** Brazilian Ministry of Planning and IBGE (2009)


---


## References & Historical Sources

### General Overview

* **[SuperWaba — Wikipedia (EN)](https://en.wikipedia.org/wiki/SuperWaba)** — Overview of the virtual machine, supported platforms, and evolution into TotalCross.
* **[Programming for Palm OS — Wikibooks](https://en.wikibooks.org/wiki/Programming_for_Palm_OS/SuperWaba)** — Historical tutorial showing how to develop SuperWaba applications in Eclipse.

---

### Project Archives

* **[SuperWaba Project on SourceForge](https://sourceforge.net/projects/superwaba/)** — Official distribution page with changelogs and downloads.
* **[SuperWaba Releases Archive (SourceForge)](https://sourceforge.net/projects/superwaba/files/)** — Version history (v3.41 to v5.85).
* **[SuperWaba.org (Archived)](https://web.archive.org/web/20080315000000*/superwaba.org)** — Snapshots of the original website, including notes on the TotalCross SDK.

---

### Academic & Institutional References

* **[PUC-Rio — Incubadora Gênesis](https://www.genesis.puc-rio.br/)** — SuperWaba listed among startups incubated at the Pontifical Catholic University of Rio de Janeiro.
* **[Maxwell PUC-Rio Repository](https://www.maxwell.vrac.puc-rio.br/)** — Academic dissertations citing SuperWaba as an incubated technology and case of internationalization.
* **[COPPEAD/UFRJ Dissertation](https://www.coppead.ufrj.br/)** — Mentions SuperWaba as an incubated company within the Gênesis program.
* **[UFSC — TCC: Desenvolvimento de Aplicações para Palm OS](https://repositorio.ufsc.br/bitstream/handle/123456789/183859/TCCEduardo_Milanese.pdf?isAllowed=y&sequence=-1)** — References SuperWaba IDE and SDK in academic context.

---

### Evolution into TotalCross

* **[TotalCross — Our History](https://totalcross.com/our-history/)** — Official statement describing the rebranding and evolution from SuperWaba.
* **[OpenSource.com (Red Hat) — “Open Source Cross-Platform Development with TotalCross”](https://opensource.com/article/20/7/totalcross-cross-platform-development)** — Article tracing the transition from SuperWaba to TotalCross and its modern applications.

---

### Community & Developer References

* **[SuperWaba — C2 Wiki](https://wiki.c2.com/?SuperWaba)** — Community summary describing it as a Java-like VM for PDAs.
* **[SuperWaba — DevMedia (PT)](https://www.devmedia.com.br/superwaba-introducao/1801)** — Classic Brazilian article explaining SuperWaba’s use on Palm OS, Windows CE, and Symbian.

---

> **Note:** The SuperWaba SDK was actively developed between 2003 and 2009, reaching version **4.50a in 2005** (used in this project) and ending at **v5.85 GPL in 2009**, before officially evolving into **TotalCross**.

---

## Disclaimer

This project is preserved for historical, academic, and educational purposes only. It represents mobile development practices from the early 2000s and should not be used for production systems.


---


## About the Author

I’m a Data Science and Analytics specialist (USP postgraduate) and Computer Engineer (UERJ) with a career spanning from **Pascal/C/Java roots** to **modern Machine Learning and AI**.

My academic and professional background includes:

- **Computation in general**
- **Machine Learning in general**
- **Hierarchical nonlinear mixed models**
- **Deep Learning, LLMs**


---

## Contact  

- [LinkedIn](https://linkedin.com/in/celso-m-silva)  
- Or open an [issue](https://github.com/celsomsilva/java-mobile-2005/issues)
