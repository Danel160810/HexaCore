export default function HexaCoreWebsite() {
  const services = [
    {
      icon: '💻',
      title: 'Desarrollo Web',
      desc: 'Páginas web modernas, optimizadas y totalmente personalizadas para empresas, comunidades y proyectos online.',
    },
    {
      icon: '🤖',
      title: 'Bots Personalizados',
      desc: 'Bots de Discord avanzados con sistemas únicos, tickets, economía, logs, automatizaciones y funciones a medida.',
    },
    {
      icon: '🛠️',
      title: 'Servidores de Discord',
      desc: 'Creamos y reformamos servidores de Discord profesionales adaptados a cualquier comunidad.',
    },
    {
      icon: '⚡',
      title: 'Hosting de Bots',
      desc: 'Hosting optimizado para bots de Discord con máximo rendimiento y soporte técnico.',
    },
    {
      icon: '🚓',
      title: 'Servidores FiveM',
      desc: 'Configuración completa de servidores FiveM con scripts, economía, optimización y diseño personalizado.',
    },
    {
      icon: '🎨',
      title: 'Texturas ERLC',
      desc: 'Diseños y texturas profesionales para Emergency Response Liberty County.',
    },
  ];

  const features = [
    'Atención personalizada',
    'Soporte profesional',
    'Diseño moderno',
    'Optimización avanzada',
    'Sistemas personalizados',
    'Servicios adaptados a cada cliente',
  ];

  return (
    <div className="min-h-screen bg-[#050505] text-white overflow-x-hidden font-sans">
      {/* HERO */}
      <section className="relative border-b border-white/10 overflow-hidden">
        <div className="absolute inset-0 bg-gradient-to-br from-cyan-500/20 via-blue-500/10 to-transparent blur-3xl" />

        <div className="relative max-w-7xl mx-auto px-6 py-28 grid lg:grid-cols-2 gap-16 items-center">
          <div>
            <div className="flex items-center gap-4 mb-8">
              <img
                src="https://i.postimg.cc/mZyJNsHg/Chat-GPT-Image-6-feb-2026-16-42-03.png"
                alt="HexaCore"
                className="w-20 h-20 rounded-3xl border border-cyan-400/30 shadow-2xl"
              />

              <div>
                <p className="text-cyan-400 uppercase tracking-[0.35em] text-sm">
                  HexaCore
                </p>
                <h2 className="text-2xl font-black">
                  Technological Innovations
                </h2>
              </div>
            </div>

            <h1 className="text-5xl lg:text-7xl font-black leading-tight mb-8">
              Donde las ideas
              <span className="text-cyan-400"> se convierten </span>
              en código.
            </h1>

            <p className="text-zinc-400 text-lg leading-relaxed max-w-2xl mb-10">
              HexaCore es una empresa especializada en desarrollo tecnológico, bots personalizados, infraestructura digital, páginas web, servidores Discord y soluciones avanzadas para comunidades y empresas.
            </p>

            <div className="flex flex-wrap gap-4">
              <a
                href="https://discord.gg/5XTgECZvyZ"
                target="_blank"
                className="bg-cyan-400 hover:bg-cyan-300 transition-all duration-300 text-black font-black px-8 py-4 rounded-2xl shadow-2xl"
              >
                Unirse al Discord
              </a>

              <button className="border border-white/20 hover:border-cyan-400 hover:text-cyan-400 transition-all duration-300 px-8 py-4 rounded-2xl">
                Ver Servicios
              </button>
            </div>
          </div>

          <div className="relative">
            <div className="bg-white/5 border border-white/10 backdrop-blur-2xl rounded-[2rem] p-8 shadow-2xl">
              <div className="flex items-center justify-between mb-8">
                <h3 className="text-3xl font-black">HexaCore Services</h3>
                <div className="w-4 h-4 rounded-full bg-green-400 animate-pulse" />
              </div>

              <div className="space-y-5">
                <div className="bg-black/40 border border-white/5 rounded-2xl p-5">
                  <p className="text-cyan-400 font-bold text-lg">🤖 Bots Personalizados</p>
                  <p className="text-zinc-400 mt-2">Sistemas exclusivos adaptados a las necesidades del cliente.</p>
                </div>

                <div className="bg-black/40 border border-white/5 rounded-2xl p-5">
                  <p className="text-cyan-400 font-bold text-lg">🌐 Desarrollo Web</p>
                  <p className="text-zinc-400 mt-2">Diseños modernos y profesionales totalmente responsive.</p>
                </div>

                <div className="bg-black/40 border border-white/5 rounded-2xl p-5">
                  <p className="text-cyan-400 font-bold text-lg">⚡ Hosting de Bots</p>
                  <p className="text-zinc-400 mt-2">Máximo rendimiento, estabilidad y soporte técnico.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* SERVICES */}
      <section className="max-w-7xl mx-auto px-6 py-24">
        <div className="mb-16 text-center">
          <p className="text-cyan-400 uppercase tracking-[0.35em] text-sm mb-4">
            Servicios
          </p>

          <h2 className="text-5xl font-black mb-6">
            ¿Qué ofrecemos?
          </h2>

          <p className="text-zinc-400 max-w-3xl mx-auto text-lg">
            Servicios tecnológicos avanzados diseñados para comunidades, empresas, servidores y proyectos digitales.
          </p>
        </div>

        <div className="grid md:grid-cols-2 xl:grid-cols-3 gap-8">
          {services.map((service, index) => (
            <div
              key={index}
              className="bg-white/[0.03] border border-white/10 rounded-[2rem] p-8 hover:border-cyan-400/40 hover:-translate-y-2 transition-all duration-300"
            >
              <div className="text-5xl mb-6">{service.icon}</div>

              <h3 className="text-3xl font-black mb-4">
                {service.title}
              </h3>

              <p className="text-zinc-400 leading-relaxed text-lg">
                {service.desc}
              </p>
            </div>
          ))}
        </div>
      </section>

      {/* ABOUT */}
      <section className="border-y border-white/10 bg-white/[0.02]">
        <div className="max-w-7xl mx-auto px-6 py-24 grid lg:grid-cols-2 gap-16 items-center">
          <div>
            <p className="text-cyan-400 uppercase tracking-[0.35em] text-sm mb-4">
              Sobre HexaCore
            </p>

            <h2 className="text-5xl font-black mb-8">
              Desarrollo profesional y soluciones reales.
            </h2>

            <p className="text-zinc-400 text-lg leading-relaxed mb-8">
              HexaCore Technological Innovations nace con el objetivo de ofrecer soluciones tecnológicas modernas, profesionales y totalmente personalizadas. Trabajamos con desarrollo de software, automatización, Discord, FiveM, páginas web y sistemas avanzados.
            </p>

            <div className="grid sm:grid-cols-2 gap-6 mt-10">
              {features.map((feature, index) => (
                <div
                  key={index}
                  className="bg-black/30 border border-white/10 rounded-2xl p-5 flex items-center gap-4"
                >
                  <div className="w-10 h-10 rounded-xl bg-cyan-400/20 flex items-center justify-center text-cyan-400 font-black">
                    ✓
                  </div>

                  <p className="font-semibold text-lg">{feature}</p>
                </div>
              ))}
            </div>
          </div>

          <div className="bg-gradient-to-br from-cyan-400/10 to-blue-500/10 border border-white/10 rounded-[2rem] p-10">
            <h3 className="text-4xl font-black mb-8">
              Hosting para Bots
            </h3>

            <div className="space-y-6 text-lg text-zinc-300">
              <p>
                ⚡ Disponemos de plazas para alojar bots de Discord.
              </p>

              <p>
                💰 Precio desde <span className="text-cyan-400 font-black">0.50€</span> por plaza.
              </p>

              <p>
                📈 Más plazas = mayor rendimiento y ventajas exclusivas.
              </p>

              <div className="pt-6 border-t border-white/10">
                <p className="text-cyan-400 font-black text-xl mb-3">
                  Opciones disponibles:
                </p>

                <ul className="space-y-3 text-zinc-300">
                  <li>• Hosting propio de HexaCore</li>
                  <li>• Hosting externo guiado</li>
                  <li>• Soporte y configuración incluida</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* LEGAL */}
      <section className="max-w-7xl mx-auto px-6 py-24">
        <div className="mb-14">
          <p className="text-cyan-400 uppercase tracking-[0.35em] text-sm mb-4">
            Legal
          </p>

          <h2 className="text-5xl font-black mb-6">
            Política y Condiciones
          </h2>

          <p className="text-zinc-400 text-lg max-w-4xl">
            HexaCore cumple con normativa GDPR, protección de datos y estándares profesionales para garantizar seguridad, transparencia y calidad en todos sus servicios.
          </p>
        </div>

        <div className="grid lg:grid-cols-3 gap-8">
          <div className="bg-white/[0.03] border border-white/10 rounded-[2rem] p-8">
            <h3 className="text-2xl font-black mb-4 text-cyan-400">
              Privacidad
            </h3>

            <p className="text-zinc-400 leading-relaxed">
              Protección de datos conforme al Reglamento General de Protección de Datos (GDPR) y uso responsable de la información.
            </p>
          </div>

          <div className="bg-white/[0.03] border border-white/10 rounded-[2rem] p-8">
            <h3 className="text-2xl font-black mb-4 text-cyan-400">
              Pagos
            </h3>

            <p className="text-zinc-400 leading-relaxed">
              Todos los pagos realizados son definitivos y sujetos a las condiciones acordadas previamente.
            </p>
          </div>

          <div className="bg-white/[0.03] border border-white/10 rounded-[2rem] p-8">
            <h3 className="text-2xl font-black mb-4 text-cyan-400">
              Seguridad
            </h3>

            <p className="text-zinc-400 leading-relaxed">
              Implementamos medidas técnicas y organizativas para proteger sistemas, datos y servicios.
            </p>
          </div>
        </div>
      </section>

      {/* CONTACT */}
      <section className="border-t border-white/10 bg-black">
        <div className="max-w-5xl mx-auto px-6 py-24 text-center">
          <h2 className="text-5xl lg:text-6xl font-black mb-8">
            ¿Listo para llevar tu proyecto al siguiente nivel?
          </h2>

          <p className="text-zinc-400 text-xl max-w-3xl mx-auto mb-12">
            Únete a HexaCore y transforma tus ideas en proyectos reales con tecnología profesional.
          </p>

          <div className="flex flex-wrap justify-center gap-5">
            <a
              href="https://discord.gg/5XTgECZvyZ"
              target="_blank"
              className="bg-cyan-400 hover:bg-cyan-300 transition-all duration-300 text-black font-black px-10 py-5 rounded-2xl text-lg shadow-2xl"
            >
              Entrar al Discord
            </a>

            <button className="border border-white/20 hover:border-cyan-400 hover:text-cyan-400 transition-all duration-300 px-10 py-5 rounded-2xl text-lg">
              Solicitar Servicio
            </button>
          </div>

          <div className="mt-16 pt-10 border-t border-white/10 text-zinc-500 text-sm">
            © 2026 HexaCore Technological Innovations — Todos los derechos reservados.
          </div>
        </div>
      </section>
    </div>
  );
}
