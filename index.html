import React, { useState, useEffect, useRef } from 'react';
import { 
  FlaskConical, 
  Menu, 
  X, 
  ArrowUpRight, 
  Lightbulb, 
  Rocket, 
  FileText, 
  BrainCircuit, 
  Scale, 
  Handshake, 
  Calendar, 
  Users, 
  ArrowRight, 
  CalendarDays, 
  MapPin, 
  Phone, 
  Mail, 
  Twitter, 
  Linkedin, 
  Instagram,
  ArrowUp,
  Eye,
  Target
} from 'lucide-react';

// --- Mock Data ---

const INITIATIVES_DATA = [
  {
    id: 1,
    title: "Design Thinking",
    description: "Workshops to foster creativity and problem-solving skills using design thinking methodologies tailored for engineering challenges.",
    icon: BrainCircuit,
    color: "text-blue-600",
    bg: "bg-blue-50",
    linkText: "Learn More"
  },
  {
    id: 2,
    title: "Pre-Incubation",
    description: "Supporting student ideas with Proof of Concept (PoC) grants, mentorship, and access to ICT's advanced laboratories.",
    icon: Rocket,
    color: "text-green-600",
    bg: "bg-green-50",
    linkText: "Apply Now"
  },
  {
    id: 3,
    title: "IPR Management",
    description: "Dedicated cell to assist faculty and students in patent search, drafting, and filing processes for their innovations.",
    icon: Scale,
    color: "text-purple-600",
    bg: "bg-purple-50",
    linkText: "IP Policy"
  },
  {
    id: 4,
    title: "Industry Linkage",
    description: "Bridging the gap between academia and industry through internships, problem statements, and collaborative research.",
    icon: Handshake,
    color: "text-orange-600",
    bg: "bg-orange-50",
    linkText: "Partners"
  },
  {
    id: 5,
    title: "Hackathons",
    description: "Organizing internal and national level Smart India Hackathons (SIH) to solve real-world problems.",
    icon: Calendar,
    color: "text-teal-600",
    bg: "bg-teal-50",
    linkText: "Upcoming"
  },
  {
    id: 6,
    title: "Entrepreneurship",
    description: "Expert talks and courses on business modeling, finance, and marketing for aspiring tech-entrepreneurs.",
    icon: Users,
    color: "text-red-600",
    bg: "bg-red-50",
    linkText: "E-Cell"
  }
];

const EVENTS_DATA = [
  {
    id: 1,
    title: "Workshop on IPR & Patent Filing",
    date: "28",
    month: "Sep",
    type: "Workshop",
    typeColor: "text-blue-600 bg-blue-50",
    subtitle: "by Dr. A. K. Srivastav"
  },
  {
    id: 2,
    title: "Angel Investment Session",
    date: "12",
    month: "Sep",
    type: "Seminar",
    typeColor: "text-green-600 bg-green-50",
    subtitle: "Guest Lecture Series"
  },
  {
    id: 3,
    title: "Prototype Submission Deadline",
    date: "05",
    month: "Aug",
    type: "Submission",
    typeColor: "text-red-600 bg-red-50",
    subtitle: "Batch 2025 Incubation"
  }
];

const TEAM_DATA = [
  {
    id: 1,
    name: "Prof. A. B. Pandit",
    role: "President, IIC",
    designation: "Vice Chancellor, ICT Mumbai",
    initials: "AP",
    bg: "bg-ict-primary"
  },
  {
    id: 2,
    name: "Prof. P. V. Devarajan",
    role: "Vice President",
    designation: "Dean, RI & C",
    initials: "PD",
    bg: "bg-gray-900"
  },
  {
    id: 3,
    name: "Dr. P. R. Gogate",
    role: "Convenor",
    designation: "Dept of Chemical Engg.",
    initials: "VG",
    bg: "bg-ict-primary"
  },
  {
    id: 4,
    name: "Dr. Neetu Jha",
    role: "Innovation Coordinator",
    designation: "Dept of Physics",
    initials: "NJ",
    bg: "bg-gray-900"
  }
];

// --- Components ---

const MolecularBackground = () => {
  const canvasRef = useRef(null);

  useEffect(() => {
    const canvas = canvasRef.current;
    const ctx = canvas.getContext('2d');
    let animationFrameId;
    let particles = [];
    
    // Connection distance threshold
    const connectDistance = 150;
    const particleCountMultiplier = 0.08; // Adjust density

    const resize = () => {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
      initParticles();
    };

    const initParticles = () => {
      particles = [];
      const count = Math.floor(window.innerWidth * particleCountMultiplier);
      for (let i = 0; i < count; i++) {
        particles.push({
          x: Math.random() * canvas.width,
          y: Math.random() * canvas.height,
          vx: (Math.random() - 0.5) * 0.5, // Velocity X
          vy: (Math.random() - 0.5) * 0.5, // Velocity Y
          size: Math.random() * 2 + 1
        });
      }
    };

    const animate = () => {
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      
      // Update and draw particles
      particles.forEach((p, i) => {
        p.x += p.vx;
        p.y += p.vy;

        // Bounce off edges
        if (p.x < 0 || p.x > canvas.width) p.vx *= -1;
        if (p.y < 0 || p.y > canvas.height) p.vy *= -1;

        // Draw particle
        ctx.beginPath();
        ctx.arc(p.x, p.y, p.size, 0, Math.PI * 2);
        ctx.fillStyle = 'rgba(128, 0, 0, 0.3)'; // ICT Red color
        ctx.fill();

        // Draw connections
        for (let j = i + 1; j < particles.length; j++) {
          const p2 = particles[j];
          const dx = p.x - p2.x;
          const dy = p.y - p2.y;
          const dist = Math.sqrt(dx * dx + dy * dy);

          if (dist < connectDistance) {
            ctx.beginPath();
            // Opacity based on distance
            ctx.strokeStyle = `rgba(128, 0, 0, ${0.15 * (1 - dist / connectDistance)})`;
            ctx.lineWidth = 1;
            ctx.moveTo(p.x, p.y);
            ctx.lineTo(p2.x, p2.y);
            ctx.stroke();
          }
        }
      });

      animationFrameId = requestAnimationFrame(animate);
    };

    window.addEventListener('resize', resize);
    resize();
    animate();

    return () => {
      window.removeEventListener('resize', resize);
      cancelAnimationFrame(animationFrameId);
    };
  }, []);

  return (
    <canvas 
      ref={canvasRef} 
      className="fixed inset-0 w-full h-full pointer-events-none z-0" 
      style={{ opacity: 0.8 }} 
    />
  );
};

const Navbar = () => {
  const [isScrolled, setIsScrolled] = useState(false);
  const [isMobileMenuOpen, setIsMobileMenuOpen] = useState(false);

  useEffect(() => {
    const handleScroll = () => {
      setIsScrolled(window.scrollY > 50);
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  }, []);

  const navLinks = [
    { name: 'Home', href: '#home' },
    { name: 'About', href: '#about' },
    { name: 'Initiatives', href: '#initiatives' },
    { name: 'Events', href: '#events' },
    { name: 'Council', href: '#team' },
  ];

  return (
    <nav className={`fixed w-full z-50 transition-all duration-300 ${isScrolled ? 'bg-white/95 backdrop-blur-md shadow-md h-16' : 'bg-transparent h-20'}`}>
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-full">
        <div className="flex justify-between items-center h-full">
          {/* Logo */}
          <div className="flex-shrink-0 flex items-center gap-3">
            <div className="w-10 h-10 md:w-12 md:h-12 bg-red-900 rounded-full flex items-center justify-center text-white shadow-lg">
              <FlaskConical size={24} />
            </div>
            <div className="flex flex-col">
              <span className="font-serif text-lg md:text-xl font-bold text-gray-900 leading-none">IIC</span>
              <span className="text-[10px] md:text-xs font-medium text-gray-500 tracking-wide uppercase">ICT Mumbai</span>
            </div>
          </div>

          {/* Desktop Menu */}
          <div className="hidden md:flex items-center space-x-8">
            {navLinks.map((link) => (
              <a key={link.name} href={link.href} className="text-gray-600 hover:text-red-900 font-medium transition text-sm lg:text-base">
                {link.name}
              </a>
            ))}
            <a href="#contact" className="px-5 py-2 bg-red-900 text-white rounded-full hover:bg-red-800 transition shadow-md font-medium text-sm">
              Contact Us
            </a>
          </div>

          {/* Mobile Menu Button */}
          <div className="md:hidden">
            <button onClick={() => setIsMobileMenuOpen(!isMobileMenuOpen)} className="text-gray-600 hover:text-gray-900 focus:outline-none">
              {isMobileMenuOpen ? <X size={28} /> : <Menu size={28} />}
            </button>
          </div>
        </div>
      </div>

      {/* Mobile Menu Panel */}
      {isMobileMenuOpen && (
        <div className="md:hidden bg-white border-t border-gray-100 shadow-xl absolute w-full">
          <div className="px-4 pt-2 pb-6 space-y-1">
            {navLinks.map((link) => (
              <a 
                key={link.name} 
                href={link.href} 
                className="block px-3 py-3 rounded-md text-base font-medium text-gray-700 hover:text-red-900 hover:bg-gray-50"
                onClick={() => setIsMobileMenuOpen(false)}
              >
                {link.name}
              </a>
            ))}
            <a 
              href="#contact" 
              className="block px-3 py-3 mt-4 text-center rounded-md text-base font-medium bg-red-900 text-white"
              onClick={() => setIsMobileMenuOpen(false)}
            >
              Contact Us
            </a>
          </div>
        </div>
      )}
    </nav>
  );
};

const Hero = () => {
  return (
    <section id="home" className="relative pt-32 pb-20 lg:pt-48 lg:pb-32 overflow-hidden bg-transparent z-10">
      {/* Background Decor - Removed solid white, kept gradients */}
      <div className="absolute inset-0 z-[-1]" style={{ background: 'radial-gradient(circle at center, transparent 0%, rgba(255,255,255,0.8) 100%)' }}></div>
      <div className="absolute top-0 right-0 -mr-20 -mt-20 w-96 h-96 bg-yellow-400 opacity-10 rounded-full blur-3xl"></div>
      <div className="absolute bottom-0 left-0 -ml-20 -mb-20 w-80 h-80 bg-red-900 opacity-10 rounded-full blur-3xl"></div>

      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative">
        <div className="text-center max-w-4xl mx-auto">
          <div className="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-red-50/90 backdrop-blur-sm text-red-900 text-sm font-semibold mb-6 border border-red-100 animate-fade-in-up">
            <span className="relative flex h-3 w-3">
              <span className="animate-ping absolute inline-flex h-full w-full rounded-full bg-red-400 opacity-75"></span>
              <span className="relative inline-flex rounded-full h-3 w-3 bg-red-600"></span>
            </span>
            Ministry of Education's Innovation Cell (MIC)
          </div>
          
          <h1 className="text-5xl md:text-7xl font-serif font-bold text-gray-900 mb-6 leading-tight">
            Innovate. Incubate. <br /> <span className="text-red-900">Impact.</span>
          </h1>
          
          <p className="text-xl text-gray-600 mb-10 max-w-2xl mx-auto leading-relaxed bg-white/30 backdrop-blur-[2px] rounded-lg p-2">
            The Institute Innovation Council of ICT Mumbai fosters a vibrant ecosystem for innovation, entrepreneurship, and start-up creation among students and faculty.
          </p>
          
          <div className="flex flex-col sm:flex-row justify-center gap-4">
            <a href="#initiatives" className="px-8 py-4 bg-red-900 text-white rounded-lg font-semibold shadow-lg hover:bg-red-800 transition transform hover:-translate-y-1">
              Explore Initiatives
            </a>
            <a href="https://mic.gov.in" target="_blank" rel="noreferrer" className="px-8 py-4 bg-white/90 backdrop-blur-sm text-gray-700 border border-gray-200 rounded-lg font-semibold shadow-sm hover:bg-white transition flex items-center justify-center gap-2">
              Visit MIC Portal <ArrowUpRight size={16} />
            </a>
          </div>
        </div>

        {/* Floating Cards (Hidden on mobile) */}
        <div className="mt-24 relative hidden md:block h-64">
          <div className="absolute left-1/2 transform -translate-x-1/2 w-full max-w-4xl grid grid-cols-3 gap-6">
            {[
              { title: "Idea Generation", desc: "Structured workshops to turn raw thoughts into viable prototypes.", icon: Lightbulb, color: "text-blue-600", bg: "bg-blue-100" },
              { title: "Incubation", desc: "World-class lab access and mentorship for early-stage startups.", icon: Rocket, color: "text-green-600", bg: "bg-green-100", offset: "-30px" },
              { title: "IPR Support", desc: "Guidance on filing patents, copyrights, and trademarks.", icon: FileText, color: "text-purple-600", bg: "bg-purple-100" }
            ].map((card, idx) => (
              <div 
                key={idx} 
                className="bg-white/95 backdrop-blur-md p-6 rounded-2xl shadow-xl border border-gray-100 transition hover:-translate-y-2 duration-500"
                style={{ marginTop: card.offset || '0px' }}
              >
                <div className={`w-12 h-12 ${card.bg} rounded-lg flex items-center justify-center ${card.color} mb-4`}>
                  <card.icon size={24} />
                </div>
                <h3 className="font-bold text-lg mb-2 text-gray-900">{card.title}</h3>
                <p className="text-sm text-gray-500">{card.desc}</p>
              </div>
            ))}
          </div>
        </div>
      </div>
    </section>
  );
};

const Stats = () => (
  <section className="bg-[#1a1a1a] py-12 border-t border-gray-800 relative z-10">
    <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div className="grid grid-cols-2 md:grid-cols-4 gap-8 text-center text-white">
        {[
          { num: "50+", label: "Startups Incubated" },
          { num: "120+", label: "Patents Filed" },
          { num: "200+", label: "Events Conducted" },
          { num: "5 Cr+", label: "Funding Raised" }
        ].map((stat, idx) => (
          <div key={idx}>
            <div className="text-4xl font-bold text-yellow-400 mb-1">{stat.num}</div>
            <div className="text-xs md:text-sm text-gray-400 uppercase tracking-wider">{stat.label}</div>
          </div>
        ))}
      </div>
    </div>
  </section>
);

const About = () => (
  <section id="about" className="py-20 bg-white relative z-10">
    <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div className="grid lg:grid-cols-2 gap-16 items-center">
        <div className="relative">
          <div className="absolute -top-4 -left-4 w-24 h-24 bg-gray-200 rounded-full opacity-20 blur-xl"></div>
          <img 
            src="https://images.unsplash.com/photo-1531482615713-2afd69097998?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80" 
            alt="ICT Mumbai Campus" 
            className="rounded-2xl shadow-2xl relative z-10 w-full object-cover h-[500px]"
          />
          <div className="absolute -bottom-6 -right-6 w-48 h-48 bg-red-900 rounded-2xl -z-0"></div>
        </div>
        <div>
          <h2 className="text-sm font-bold text-red-900 uppercase tracking-wider mb-2">Who We Are</h2>
          <h3 className="text-3xl md:text-4xl font-serif font-bold text-gray-900 mb-6">Institute of Chemical Technology</h3>
          <p className="text-gray-600 mb-6 leading-relaxed">
            Established under the Ministry of Education's Innovation Cell (MIC), the IIC at ICT Mumbai is dedicated to creating a systematic path for innovation. We envision an educational system where students don't just seek jobs, but create them.
          </p>
          
          <div className="space-y-6 mt-8">
            <div className="flex">
              <div className="flex-shrink-0">
                <div className="flex items-center justify-center h-12 w-12 rounded-md bg-red-100 text-red-900">
                  <Eye size={20} />
                </div>
              </div>
              <div className="ml-4">
                <h4 className="text-lg leading-6 font-medium text-gray-900">Our Vision</h4>
                <p className="mt-2 text-base text-gray-500">
                  To be a global center of excellence in chemical technology innovation and entrepreneurship.
                </p>
              </div>
            </div>
            <div className="flex">
              <div className="flex-shrink-0">
                <div className="flex items-center justify-center h-12 w-12 rounded-md bg-yellow-100 text-yellow-700">
                  <Target size={20} />
                </div>
              </div>
              <div className="ml-4">
                <h4 className="text-lg leading-6 font-medium text-gray-900">Our Mission</h4>
                <p className="mt-2 text-base text-gray-500">
                  To conduct various innovation and entrepreneurship-related activities and organize periodic workshops/seminars.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
);

const Initiatives = () => (
  <section id="initiatives" className="py-20 bg-gray-50 relative z-10">
    <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div className="text-center mb-16">
        <h2 className="text-sm font-bold text-red-900 uppercase tracking-wider mb-2">What We Do</h2>
        <h3 className="text-3xl md:text-4xl font-serif font-bold text-gray-900">Key Functional Areas</h3>
        <p className="mt-4 max-w-2xl mx-auto text-gray-500">Comprehensive support system covering the entire lifecycle of innovation.</p>
      </div>

      <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        {INITIATIVES_DATA.map((item) => (
          <div key={item.id} className="bg-white rounded-xl shadow-sm hover:shadow-xl transition duration-300 p-8 border border-gray-100 group">
            <div className={`w-14 h-14 ${item.bg} rounded-xl flex items-center justify-center ${item.color} mb-6 group-hover:scale-110 transition`}>
              <item.icon size={28} />
            </div>
            <h4 className="text-xl font-bold text-gray-900 mb-3">{item.title}</h4>
            <p className="text-gray-600 text-sm leading-relaxed mb-4">
              {item.description}
            </p>
            <a href="#" className={`${item.color} font-semibold text-sm hover:opacity-80 flex items-center gap-1`}>
              {item.linkText} <ArrowRight size={14} />
            </a>
          </div>
        ))}
      </div>
    </div>
  </section>
);

const Events = () => (
  <section id="events" className="py-20 bg-white relative z-10">
    <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div className="flex justify-between items-end mb-12">
        <div>
          <h2 className="text-sm font-bold text-red-900 uppercase tracking-wider mb-2">Activity Calendar</h2>
          <h3 className="text-3xl md:text-4xl font-serif font-bold text-gray-900">Recent & Upcoming Events</h3>
        </div>
        <a href="#" className="hidden md:inline-flex items-center font-medium text-red-900 hover:text-red-700 transition">
          View All Events <ArrowRight size={16} className="ml-2" />
        </a>
      </div>

      <div className="flex flex-col lg:flex-row gap-8">
        {/* Featured Event */}
        <div className="lg:w-2/3 relative group overflow-hidden rounded-2xl shadow-lg cursor-pointer">
          <img 
            src="https://images.unsplash.com/photo-1544531586-fde5298cdd40?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" 
            alt="Hackathon" 
            className="w-full h-[400px] object-cover transition duration-500 group-hover:scale-105" 
          />
          <div className="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent flex flex-col justify-end p-8">
            <span className="inline-block px-3 py-1 bg-yellow-400 text-black text-xs font-bold rounded mb-3 w-max">UPCOMING</span>
            <h3 className="text-2xl font-bold text-white mb-2">Smart India Hackathon 2025 - Internal Round</h3>
            <p className="text-gray-200 mb-4 line-clamp-2">The biggest open innovation model is back. Register your teams for the internal selection process at ICT Mumbai.</p>
            <div className="flex items-center text-gray-300 text-sm gap-4">
              <span className="flex items-center"><CalendarDays size={16} className="mr-2" /> Oct 15, 2025</span>
              <span className="flex items-center"><MapPin size={16} className="mr-2" /> KV Auditorium</span>
            </div>
          </div>
        </div>

        {/* Side Events List */}
        <div className="lg:w-1/3 flex flex-col gap-4">
          {EVENTS_DATA.map((event) => (
            <div key={event.id} className="bg-gray-50 p-5 rounded-xl border border-gray-100 flex gap-4 hover:shadow-md transition cursor-pointer">
              <div className="flex-shrink-0 w-16 h-16 bg-white rounded-lg flex flex-col items-center justify-center border border-gray-200 shadow-sm text-center">
                <span className="text-xs font-bold text-gray-400 uppercase">{event.month}</span>
                <span className="text-xl font-bold text-red-900">{event.date}</span>
              </div>
              <div>
                <h4 className="font-bold text-gray-900 text-sm leading-tight mb-1">{event.title}</h4>
                <p className="text-xs text-gray-500 mb-2">{event.subtitle}</p>
                <span className={`text-xs font-medium px-2 py-1 rounded ${event.typeColor}`}>{event.type}</span>
              </div>
            </div>
          ))}
        </div>
      </div>
      
      <div className="mt-8 text-center md:hidden">
        <a href="#" className="inline-flex items-center font-medium text-red-900 hover:text-red-700 transition">
          View All Events <ArrowRight size={16} className="ml-2" />
        </a>
      </div>
    </div>
  </section>
);

const Team = () => (
  <section id="team" className="py-20 bg-gray-50 relative z-10">
    <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div className="text-center mb-16">
        <h2 className="text-sm font-bold text-red-900 uppercase tracking-wider mb-2">Leadership</h2>
        <h3 className="text-3xl md:text-4xl font-serif font-bold text-gray-900">The Council</h3>
        <p className="mt-4 max-w-2xl mx-auto text-gray-500">Guided by distinguished faculty and driven by enthusiastic students.</p>
      </div>

      <h4 className="text-xl font-bold text-gray-800 mb-8 border-l-4 border-red-900 pl-4">Faculty Representation</h4>
      <div className="grid md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
        {TEAM_DATA.map((member) => (
          <div key={member.id} className="bg-white p-6 rounded-xl shadow-sm text-center border border-gray-100 hover:shadow-md transition group">
             <div className={`w-24 h-24 rounded-full mx-auto mb-4 border-4 border-gray-50 flex items-center justify-center text-white text-2xl font-bold ${member.bg} group-hover:scale-105 transition`}>
                {member.initials}
             </div>
            <h5 className="font-bold text-lg text-gray-900">{member.name}</h5>
            <p className="text-red-900 text-sm font-medium mb-2">{member.role}</p>
            <p className="text-xs text-gray-500">{member.designation}</p>
          </div>
        ))}
      </div>

      <div className="bg-white rounded-xl shadow-sm p-8 border border-gray-100 flex flex-col md:flex-row items-center justify-between">
        <div>
          <h4 className="text-xl font-bold text-gray-900 mb-2">Student Council</h4>
          <p className="text-gray-600">A dedicated team of 20+ student coordinators driving innovation on campus.</p>
        </div>
        <div className="mt-4 md:mt-0 flex -space-x-2 overflow-hidden">
          {[1,2,3,4].map(i => (
            <div key={i} className="inline-block h-10 w-10 rounded-full ring-2 ring-white bg-gray-300 flex items-center justify-center text-gray-600 text-xs font-bold">
               SC
            </div>
          ))}
          <div className="h-10 w-10 rounded-full bg-gray-100 flex items-center justify-center text-xs font-bold text-gray-600 ring-2 ring-white">+16</div>
        </div>
      </div>
    </div>
  </section>
);

const Footer = () => (
  <footer id="contact" className="bg-[#1a1a1a] text-gray-300 pt-16 pb-8 relative z-10">
    <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div className="grid md:grid-cols-2 lg:grid-cols-4 gap-12 mb-12">
        {/* Branding */}
        <div>
          <div className="flex items-center gap-2 mb-6">
            <FlaskConical className="text-yellow-400" size={24} />
            <span className="text-white text-xl font-serif font-bold">IIC ICT Mumbai</span>
          </div>
          <p className="text-sm leading-relaxed mb-6 text-gray-400">
            Fostering the culture of Innovation among students and faculty of the Institute of Chemical Technology.
          </p>
          <div className="flex space-x-4">
            {[Twitter, Linkedin, Instagram].map((Icon, i) => (
              <a key={i} href="#" className="w-8 h-8 rounded bg-gray-800 flex items-center justify-center hover:bg-red-900 transition">
                <Icon size={16} />
              </a>
            ))}
          </div>
        </div>

        {/* Links */}
        <div>
          <h4 className="text-white font-bold mb-6">Quick Links</h4>
          <ul className="space-y-3 text-sm">
            {['Home', 'About IIC', 'MIC Portal', 'Startup Policy', 'YUKTI 2.0'].map(link => (
              <li key={link}><a href="#" className="hover:text-yellow-400 transition">{link}</a></li>
            ))}
          </ul>
        </div>

        {/* Contact */}
        <div>
          <h4 className="text-white font-bold mb-6">Contact Us</h4>
          <ul className="space-y-4 text-sm">
            <li className="flex items-start gap-3">
              <MapPin size={16} className="mt-1 text-yellow-400" />
              <span>Nathalal Parekh Marg, Matunga,<br />Mumbai - 400019, India</span>
            </li>
            <li className="flex items-center gap-3">
              <Phone size={16} className="text-yellow-400" />
              <span>+91 22 3361 1111</span>
            </li>
            <li className="flex items-center gap-3">
              <Mail size={16} className="text-yellow-400" />
              <span>iic@ictmumbai.edu.in</span>
            </li>
          </ul>
        </div>

        {/* Newsletter */}
        <div>
          <h4 className="text-white font-bold mb-6">Stay Updated</h4>
          <p className="text-sm text-gray-400 mb-4">Subscribe to get notifications about upcoming hackathons and grants.</p>
          <form className="flex flex-col gap-2" onSubmit={(e) => { e.preventDefault(); alert('Subscribed!'); }}>
            <input 
              type="email" 
              placeholder="Enter your email" 
              className="bg-gray-800 border border-gray-700 text-white px-4 py-2 rounded focus:outline-none focus:border-yellow-400"
            />
            <button type="submit" className="bg-red-900 hover:bg-red-800 text-white px-4 py-2 rounded transition font-medium">
              Subscribe
            </button>
          </form>
        </div>
      </div>

      <div className="border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between items-center text-sm text-gray-500">
        <p>&copy; 2024 IIC - ICT Mumbai. All rights reserved.</p>
        <div className="mt-4 md:mt-0 space-x-6">
          <a href="#" className="hover:text-white">Privacy Policy</a>
          <a href="#" className="hover:text-white">Terms of Service</a>
        </div>
      </div>
    </div>
  </footer>
);

const BackToTop = () => {
  const [visible, setVisible] = useState(false);

  useEffect(() => {
    const toggleVisible = () => setVisible(window.scrollY > 300);
    window.addEventListener('scroll', toggleVisible);
    return () => window.removeEventListener('scroll', toggleVisible);
  }, []);

  return (
    <button 
      onClick={() => window.scrollTo({ top: 0, behavior: 'smooth' })}
      className={`fixed bottom-8 right-8 bg-yellow-400 text-black w-10 h-10 rounded-full shadow-lg items-center justify-center hover:bg-yellow-500 transition z-40 ${visible ? 'flex' : 'hidden'}`}
    >
      <ArrowUp size={20} />
    </button>
  );
};

// --- Main App Component ---

export default function App() {
  return (
    <div className="font-sans text-gray-800 antialiased bg-gray-50 relative min-h-screen">
      <MolecularBackground />
      <Navbar />
      <Hero />
      <Stats />
      <About />
      <Initiatives />
      <Events />
      <Team />
      <Footer />
      <BackToTop />
    </div>
  );
}
