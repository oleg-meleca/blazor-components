# Blazor Components

(Română) **Blazor Components** este un proiect dedicat dezvoltării și furnizării de componente reutilizabile pentru framework-ul Blazor. Aceste componente au scopul de a facilita crearea de aplicații web moderne, oferind dezvoltatorilor un set de instrumente predefinite și ușor de utilizat pentru a accelera procesul de dezvoltare.

(English) **Blazor Components** is a project dedicated to developing and providing reusable components for the Blazor framework. These components aim to facilitate the creation of modern web applications by providing developers with a set of predefined and easy-to-use tools to speed up the development process.

## Descriere (Română)

Acest proiect include o colecție variată de componente UI pentru Blazor, construite pentru a fi flexibile și extensibile, adresând nevoile atât ale aplicațiilor simple, cât și ale celor complexe. Fiecare componentă este proiectată pentru a fi utilizată cu ușurință în diverse scenarii de dezvoltare și se integrează nativ în ecosistemul Blazor, profitând de toate avantajele acestuia.

## Description (English)

This project includes a diverse collection of UI components for Blazor, built to be flexible and extensible, addressing the needs of both simple and complex applications. Each component is designed to be easily utilized in various development scenarios and integrates natively into the Blazor ecosystem, taking advantage of all its benefits.

## Caracteristici (Română)

- **Reutilizare**: Toate componentele sunt create pentru a putea fi reutilizate și integrate în diverse proiecte Blazor.
- **Personalizare**: Componentele sunt configurabile și ușor de stilizat, oferind dezvoltatorilor flexibilitate în adaptarea lor la nevoile specifice.
- **Performanță**: Optimizate pentru o performanță ridicată și o utilizare eficientă a resurselor.
- **Documentație Detaliată**: Fiecare componentă include documentație și exemple de utilizare pentru o integrare rapidă.

## Features (English)

- **Reusability**: All components are designed to be reusable and integrated into various Blazor projects.
- **Customization**: Components are configurable and easy to style, giving developers flexibility in adapting them to specific needs.
- **Performance**: Optimized for high performance and resource efficiency.
- **Detailed Documentation**: Each component includes documentation and usage examples for quick integration.

## Cum să folosești (Română)

1. Clonează acest depozit:
   ```bash
   git clone https://github.com/oleg-meleca/blazor-components.git
Acest proiect este în continuă dezvoltare, și vom adăuga în mod regulat noi componente și îmbunătățiri. Îți mulțumim pentru interesul tău și sperăm ca Blazor Components să fie de ajutor în proiectele tale!

## How to use (English)

1. Clone this repository:
   ```bash
   git clone https://github.com/oleg-meleca/blazor-components.git
This project is under continuous development, and we will regularly add new components and improvements. Thank you for your interest and we hope Blazor Components will be helpful in your projects!

## Licență (Română)
Acest proiect este licențiat sub Licența MIT.

## License (English)
This project is licensed under the MIT License.

## Lista componentelor de baza (RO)
1. Componente de bază pentru UI

    - **Button** : Buton simplu pentru acțiuni.
    - **InputText, InputNumber, InputDate** : Componente pentru inputuri de text, numere și date.
    - **Checkbox, RadioButton** : Componente pentru selecții binare sau opțiuni multiple.
    - **Select** : Listă derulantă pentru opțiuni.
    - **Slider** : Selector pentru intervale numerice.

2. Formulare și validare

    - **EditForm** : Container pentru formulare.
    - **DataAnnotationsValidator** : Validator bazat pe DataAnnotations.
    - **ValidationSummary** : Rezumat al erorilor de validare.
    - **InputFile** : Componetă pentru upload de fișiere.

3. Afișare de date

    - **DataGrid** : Tabel interactiv pentru afișarea și manipularea datelor.
    - **Table** : Tabel simplu, customizabil.
    - **Chart** : Grafic pentru vizualizarea datelor (necesită biblioteci externe, cum ar fi Chart.js).
    - **Pagination** : Componenetă pentru paginarea datelor.

4. Navigare și layout

    - **NavLink** : Link pentru navigarea în aplicație.
    - **Router** : Manager pentru rute.
    - **Layout** : Template-uri pentru structura paginii.
    - **Tab** : Interfață pentru organizarea pe file.

5. Interacțiuni și feedback

    - **Dialog / Modal** : Fereastră pentru confirmări și informații suplimentare.
    - **Toast / Notification** : Mesaje de notificare.
    - **Loading Spinner** : Indicator de încărcare.

6. Componente multimedia și avansate

    - **Image** : Componentă pentru afișarea de imagini.
    - **Video / Audio** : Componentă pentru fișiere media.
    - **Carousel** : Galerie de imagini.
    - **Map** : Componentă pentru hărți (de obicei integrează API-uri externe, cum ar fi Google Maps).

7. Autentificare și autorizare

    - **AuthorizeView** : Componentă pentru controlul accesului la vizualizare.
    - **CascadingAuthenticationState** : Pentru gestionarea stării de autentificare.

8. Internaționalizare și localizare

    - **Localization** : Resurse și componente pentru traducerea aplicației.
  

##Lista de componente avansate - pentru a extinde funcționalitatea aplicației, utile în proiecte complexe sau aplicații comerciale:

### 1. **Componente de date avansate**
   - **TreeView** - Afișare ierarhică a datelor, utilă pentru structuri de tip arborescent.
   - **Timeline** - Afișarea evenimentelor într-o linie temporală.
   - **Scheduler / Calendar** - Programator de evenimente, ideal pentru aplicații de management al timpului.
   - **Kanban Board** - Componentă pentru vizualizarea și organizarea sarcinilor.

### 2. **Componente grafice și de raportare**
   - **Heatmap** - Vizualizare a datelor în funcție de intensitate.
   - **Pie Chart, Bar Chart, Line Chart** - Grafic pentru vizualizarea de tip sectoare, bare și linii.
   - **Report Viewer** - Componentă pentru afișarea de rapoarte (necesită un serviciu de generare de rapoarte).

### 3. **Componente de date avansate pentru formulare**
   - **AutoComplete** - Căutare și completare automată în câmpurile de input.
   - **Tag Input** - Permite adăugarea de etichete multiple.
   - **Color Picker** - Selector de culori.
   - **Range Slider** - Selector pentru intervale personalizate.
   - **Rating** - Componentă pentru evaluarea cu stele sau note.

### 4. **Componente pentru experiența utilizatorului**
   - **Stepper** - Componentă pentru ghidarea utilizatorului prin pași succesivi.
   - **Progress Bar** - Bară de progres, utilă pentru sarcini care durează mai mult.
   - **Breadcrumbs** - Indicator al poziției curente în structura aplicației.
   - **Accordions și Expander** - Organizarea conținutului într-un format pliabil.
   - **Floating Action Button** - Buton de acțiune, folosit frecvent în aplicațiile mobile.

### 5. **Componente pentru tabele și liste avansate**
   - **MultiSelect List** - Listă cu selecție multiplă.
   - **Virtual Scrolling** - Încărcarea dinamică a datelor în tabele și liste mari pentru performanță mai bună.
   - **Context Menu** - Meniu contextual activat prin click-dreapta.
   - **Filter Panel** - Panou de filtrare pentru tabele și liste de date.

### 6. **Componente de integrare și interacțiune cu sistemul**
   - **QRCode / Barcode Generator** - Generarea de coduri QR sau coduri de bare.
   - **File Manager** - Gestionare de fișiere și foldere.
   - **PDF Viewer** - Vizualizare și interacțiune cu fișiere PDF.
   - **Drag-and-Drop** - Permite utilizatorilor să reordoneze elementele vizuale.

### 7. **Componente pentru integrarea cu servicii externe**
   - **Chatbot** - Componentă pentru chat (poate fi integrată cu servicii de AI).
   - **Social Media Sharing Buttons** - Butoane de partajare pentru rețelele de socializare.
   - **Map Viewer Avansat** - Vizualizare hărți cu opțiuni pentru puncte de interes și trasee.

### 8. **Componente pentru aplicații de afaceri**
   - **Pivot Grid** - Grilă pivot pentru analiza datelor complexe.
   - **Financial Chart** - Grafice pentru date financiare (cum ar fi stocuri, rate de schimb etc.).
   - **Org Chart** - Diagramă ierarhică pentru structuri organizaționale.
   - **Rich Text Editor** - Editor avansat de text cu opțiuni de formatare.

Aceste componente aduc un plus de interactivitate și sunt disponibile prin dezvoltare custom,care oferă suport extins și funcționalități avansate pentru Blazor.
