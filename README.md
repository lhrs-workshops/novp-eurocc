# Napredna obdelava velepodatkov v Pythonu

Spoznali boste različne načine pohitritve nalaganja večjih podatkovnih zbirk s knjižnico Pandas. Nadalje bodo predstavljeni načini dodatnih pohitritev dela z večjimi podatkovnimi zbirkami, ki jih omogočata knjižnici Polars in cuDF. Udeleženci bodo s primerjavo izvedbe funkcij za delo s podatki v omenjenih knjižnicah spoznali prednosti in slabosti posameznih pristopov za obdelavo velepodatkov.

<div style="text-align: center;">
    <p">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/320px-Pandas_logo.svg.png" alt="Pandas" width="30%"/>
    </p>
    <p>
        <img src="https://raw.githubusercontent.com/pola-rs/polars-static/master/logos/polars_github_logo_rect_dark_name.svg" alt="Polars" width="30%" />
    </p>
    <p>
        <img src="https://docs.rapids.ai/api/cudf/stable/_images/RAPIDS-logo-purple.png" alt="RAPIDS cuDF" width="30%" />
    </p>
</div>

---

Izobraževanje je sestavljeno iz več manjših enot. Vsaka enota ima pripadajoč Jupyter Notebook zvezek v katerem je podana snov s primeri. V zvezkih so tudi krajši primeri in naloge za utrjevanje snovi. 

# Vsebina

* [0 - Priprava izvajalnega okolja](0-Priprava_izvajalnega_okolja.md) *(priporočamo uporabo [Google Colab](https://colab.research.google.com); CPE in GPE!)*
* [1 - Napredne funkcionalnosti Pandas](1-Napredne_funkcionalnosti_Pandas.ipynb)
    * [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lhrs-workshops/novp-eurocc/blob/main/1-Napredne_funkcionalnosti_Pandas.ipynb)
    * optimizacija podatkovnih tipov
    * veriženje funkcij
    * napredne funkcije (.apply(), .query())
* [2 - Primerjava datotečnih formatov velepodatkovnih zbirk](2-Primerjava_datotečnih_formatov.ipynb)
    * [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lhrs-workshops/novp-eurocc/blob/main/2-Primerjava_datotečnih_formatov.ipynb)
    * CSV, Pickle, Parquet in Feather
* [3 - Knjižnica Polars in primerjava s Pandas](3-Knjižnica_Polars_in_primerjava_s_Pandas.ipynb)
    * [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lhrs-workshops/novp-eurocc/blob/main/3-Knjižnica_Polars_in_primerjava_s_Pandas.ipynb)
    * izboljšave Polars v primerjavi s Pandas
    * delo s Polars in podobnosti s Pandas
* [4 - Obdelava velepodatkov z GPE (knjižnica cuDF)](4-Obdelava_velepodatkov_z_GPE.ipynb)
    * [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lhrs-workshops/novp-eurocc/blob/main/4-Obdelava_velepodatkov_z_GPE.ipynb)
    * knjižnica Pandas in cuDF (NVIDIA RAPIDS)
    * izvajanje na CPE in GPE

---

> Izobraževanje se izvaja v okviru projekta EuroCC 2, ki je financiran s strani Evropske Unije in EuroHPC Joint Undertaking.  

![EuroCC2](https://www.sling.si/wp-content/uploads/2023/03/logoti.png)