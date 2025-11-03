import React, { useState, useEffect, useRef } from "react";

export default function AudioPortfolio() {
  const [filter, setFilter] = useState({ section: "Todas", year: "Todos" });
  const [showTopButton, setShowTopButton] = useState(false);
  const [menuOpen, setMenuOpen] = useState(false);
  const [filteredItems, setFilteredItems] = useState([]);
  const [animating, setAnimating] = useState(false);

  const sidebarRef = useRef(null);

  // ======= Dados completos =======
  const audiovisual = [
    { title: "Um Filme de BR", role: "Pós-produção de Áudio", year: "2025", description: "Documentário longa-metragem de Wender Zanon (Canoas-RS).", link: "http://imdb.com/title/tt8114480/fullcredits?ref_=tt_cl_sm#cast" },
    { title: "Ensaios Sobre Uma Cidade", role: "Pós-produção de Áudio", year: "2024", description: "Curta documentário de Wender Zanon (Canoas-RS).", link: "http://youtu.be/s9QQOOeqh0w" },
    { title: "This Is Canoas Not POA", role: "Pós-produção de Áudio", year: "2021", description: "Documentário longa-metragem de Wender Zanon.", link: "http://youtu.be/Bo4mRjjIRiA" },
    { title: "Sem Abrigo", role: "Trilha Original", year: "2017", description: "Curta de Leonardo Remor. Trilha 'V', dpsmkr. Premiado no 46º Festival de Cinema de Gramado.", link: "http://dpsmkr.bandcamp.com/track/v" },
    { title: "White", role: "Trilha Original", year: "2017", description: "Curta de Jaasiel Andrade. Trilha 'White', AKAAO.", link: "http://akaao.bandcamp.com/track/white" },
    { title: "As coisas que não me deixam", role: "Trilha Original", year: "2017", description: "Curta de Jeison Placinsch. Trilha 'Sem Título', dpsmkr." }
  ];

  const albums = [
    { title: "Idade da Desordem", artist: "Idade da Desordem", role: "Produção, Gravação, Edição, Mixagem, Masterização", year: "2025", link: "https://idadedadesordem.bandcamp.com/album/idade-da-desordem" },
    { title: "The Completers", artist: "The Completers", role: "Produção, Gravação, Edição, Mixagem", year: "2025", link: "http://thecompleters.bandcamp.com/album/the-completers" },
    { title: "deumdentrodooutro", artist: "Mal dos Trópicos", role: "Produção, Gravação, Edição, Mixagem, Masterização", year: "2024", link: "https://maldostropicos.bandcamp.com/album/deumdentrodooutro" },
    { title: "13072024", artist: "dpsmkr", role: "Composição, Gravação, Edição, Mixagem, Masterização", year: "2024", link: "http://dpsmkr.bandcamp.com/album/13072024-live" },
    { title: "Cortina de Fumaça", artist: "Cortina de Fumaça", role: "Composição, Gravação, Edição, Mixagem, Masterização", year: "2024", link: "http://cortinadefumaca.bandcamp.com/album/cortina-de-fuma-a" },
    { title: "The Count", artist: "The Count", role: "Composição, Gravação, Edição, Mixagem, Masterização", year: "2024", link: "http://the-count.bandcamp.com/album/the-count" },
    { title: "Aggressive & Top", artist: "MÄSKARA", role: "Composição, Pré-produção, Produção", year: "2023", link: "http://maskarabr.bandcamp.com/album/aggressive-top" },
    { title: "04122022", artist: "dpsmkr", role: "Composição, Gravação, Edição, Mixagem, Masterização", year: "2022", link: "http://dpsmkr.bandcamp.com/album/04122022-live" }
  ];

  const eps = [
    { title: "vol. 5", artist: "dpsmkr", role: "Composição, Gravação, Edição, Mixagem, Masterização", year: "2021" },
    { title: "1554", artist: "dpsmkr", role: "Composição, Gravação, Edição, Mixagem, Masterização", year: "2020" },
    { title: "#1", artist: "Duplo Binário", role: "Mixagem, Masterização", year: "2019" },
    { title: "Tropical Noir", artist: "Paquetá", role: "Pré-produção, Produção, Gravação, Edição, Mixagem, Masterização", year: "2019" },
    { title: "S/T", artist: "Conflito", role: "Pré-produção, Produção, Composição, Edição, Mixagem, Masterização", year: "2019" }
  ];

  const singles = [
    { title: "Faixa Bônus", artist: "Paquetá", role: "Masterização", year: "2019" },
    { title: "Neal! Allen!", artist: "Cruise Noir", role: "Composição, Programação, Gravação, Edição, Mixagem, Masterização", year: "2018" },
    { title: "Computer Music", artist: "Cruise Noir", role: "Composição, Programação, Gravação, Edição, Mixagem, Masterização", year: "2017" },
    { title: "赤青", artist: "AKAAO", role: "Composição, Gravação, Edição, Mixagem, Masterização", year: "2018" }
  ];

  const podcasts = [
    { title: "This is Canoas Podcast", role: "Gravação, Edição, Mixagem", year: "2021" }
  ];

  const splits = [
    { title: "dpsmkr vs. corpo celeste", role: "Composição, Gravação, Edição, Mixagem, Masterização", year: "2019" },
    { title: "Revolcadas / G. Paim / Ariel Teske + G. Paim", role: "Gravação, Edição, Mixagem, Masterização", year: "2018" }
  ];

  const sections = [
    { name: "Todas", items: [...audiovisual, ...albums, ...eps, ...singles, ...podcasts, ...splits] },
    { name: "Audiovisual", items: audiovisual },
    { name: "Álbuns", items: albums },
    { name: "EPs / Mini-álbuns", items: eps },
    { name: "Singles / Faixas", items: singles },
    { name: "Podcasts", items: podcasts },
    { name: "Splits / Colaborações", items: splits }
  ];

  const years = ["Todos","2025","2024","2023","2022","2021","2020","2019","2018","2017","2016","2015","2014","2013"];

  // ======= Filtro com animação =======
  const applyFilter = (newFilter) => {
    setAnimating(true);
    setTimeout(() => {
      setFilter(newFilter);
      setAnimating(false);
      // Scroll suave para o topo do conteúdo
      window.scrollTo({ top: 0, behavior: "smooth" });
      // Scroll na sidebar para o filtro ativo
      if (sidebarRef.current) {
        const activeButton = sidebarRef.current.querySelector(".active-filter");
        if (activeButton) activeButton.scrollIntoView({ behavior: "smooth", block: "center" });
      }
    }, 300); // tempo do fade-out
  };

  useEffect(() => {
    let items = sections.find(sec => sec.name === filter.section)?.items || [];
    if (filter.year !== "Todos") items = items.filter(item => item.year === filter.year);
    setFilteredItems(items);
  }, [filter]);

  useEffect(() => {
    const handleScroll = () => setShowTopButton(window.scrollY > 300);
    window.addEventListener("scroll", handleScroll);
    return () => window.removeEventListener("scroll", handleScroll);
  }, []);

  const scrollToTop = () => window.scrollTo({ top: 0, behavior: "smooth" });

  return (
    <div className="min-h-screen flex flex-col md:flex-row bg-gradient-to-r from-gray-100 via-gray-50 to-gray-100 text-gray-900 relative">

      {/* Overlay mobile */}
      {menuOpen && <div onClick={() => setMenuOpen(false)} className="fixed inset-0 bg-black bg-opacity-40 z-40 transition-opacity"></div>}

      {/* Header mobile */}
      <header className="md:hidden flex items-center justify-between bg-blue-600 text-white p-4 shadow-lg z-50 relative">
        <h1 className="font-bold text-lg">Portfólio de Áudio</h1>
        <button onClick={() => setMenuOpen(!menuOpen)} className="text-white text-2xl font-bold">☰</button>
      </header>

      {/* Sidebar */}
      <aside ref={sidebarRef} className={`w-64 bg-gradient-to-b from-blue-600 to-blue-400 text-white shadow-lg p-6 md:h-screen overflow-auto fixed md:relative z-50 transform transition-transform duration-300 ease-in-out ${menuOpen ? "translate-x-0" : "-translate-x-full md:translate-x-0"}`}>
        <h2 className="text-2xl font-bold mb-4">Seções</h2>
        {sections.map((sec, i) => (
          <button key={i} className={`block w-full text-left py-2 mb-2 px-3 rounded-lg transition-all duration-200 ${filter.section === sec.name ? 'bg-white text-blue-600 shadow-lg active-filter' : 'hover:bg-white hover:text-blue-600'}`} onClick={() => applyFilter({ ...filter, section: sec.name })}>{sec.name}</button>
        ))}
        <h2 className="text-2xl font-bold mt-6 mb-2">Ano</h2>
        {years.map((y, i) => (
          <button key={i} className={`block w-full text-left py-2 mb-2 px-3 rounded-lg transition-all duration-200 ${filter.year === y ? 'bg-white text-blue-600 shadow-lg active-filter' : 'hover:bg-white hover:text-blue-600'}`} onClick={() => applyFilter({ ...filter, year: y })}>{y}</button>
        ))}
      </aside>

      {/* Main content */}
      <main className="flex-1 p-6 md:p-8 md:ml-64">
        <h1 className="text-3xl md:text-4xl font-extrabold mb-6">Portfólio de Áudio — Jonas A. Dalacorte</h1>
        <div className={`grid gap-6 sm:grid-cols-2 lg:grid-cols-3 transition-opacity duration-300 ${animating ? 'opacity-0' : 'opacity-100'}`}>
          {filteredItems.map((item, i) => (
            <div key={i} style={{ animationDelay: `${i*50}ms` }} className="bg-white p-5 rounded-2xl shadow-md hover:shadow-xl transition-all duration-500 transform hover:-translate-y-1 opacity-0 animate-fadeIn">
              <h3 className="font-semibold text-lg md:text-xl">{item.title}{item.artist ? ` — ${item.artist}` : ''}</h3>
              <div className="text-sm md:text-base text-gray-500 mt-1">{item.role} • {item.year}</div>
              {item.description && <p className="mt-2 text-sm md:text-base text-gray-700">{item.description}</p>}
              {item.link && <a href={item.link} target="_blank" rel="noreferrer" className="text-blue-600 text-sm md:text-base underline mt-2 inline-block">Ouvir / Ver</a>}
            </div>
          ))}
        </div>
      </main>

      {/* Botão Topo */}
      {showTopButton && <button onClick={scrollToTop} className="fixed bottom-8 right-8 bg-blue-600 text-white p-3 rounded-full shadow-lg hover:bg-blue-500 transition-colors">↑ Topo</button>}

      <style jsx>{`
        @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
        .animate-fadeIn { animation: fadeIn 0.6s ease forwards; }
      `}</style>
    </div>
  );
}
