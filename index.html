import { useState, useEffect, useRef } from "react";
 
const COLORS = {
  bg: "#0c0c0f",
  surface: "#131318",
  border: "#1e1e26",
  white: "#eeeaf2",
  muted: "#6b6878",
  accent: "#c084fc",
  accent2: "#818cf8",
  accent3: "#34d399",
};
 
const skills = [
  { name: "PHP (Laravel / CodeIgniter / Core)", pct: 95 },
  { name: "Oracle Apex", pct: 88 },
  { name: "MySQL / Oracle DB", pct: 90 },
  { name: "ERP Systems", pct: 92 },
  { name: "API Integration", pct: 85 },
  { name: "Git / Linux", pct: 80 },
  { name: "HTML / CSS", pct: 82 },
];
 
const tags = [
  { label: "PHP", hl: true },
  { label: "Laravel", hl: true },
  { label: "CodeIgniter", hl: true },
  { label: "Oracle Apex", hl: true },
  { label: "MySQL" }, { label: "Oracle DB" }, { label: "ERP" },
  { label: "CRM" }, { label: "POS" }, { label: "API Integration" },
  { label: "REST APIs" }, { label: "Git" }, { label: "Linux" },
  { label: "HTML5" }, { label: "CSS3" }, { label: "Sales Module" },
  { label: "Purchase Module" }, { label: "General Ledger" },
  { label: "Inventory" }, { label: "Team Lead" },
];
 
const expertise = [
  {
    icon: "⚙️",
    title: "PHP & ERP Development",
    desc: "Extensive experience in PHP and ERP systems, including CodeIgniter, Laravel, and Oracle Apex — delivering production-grade business applications.",
  },
  {
    icon: "👥",
    title: "Team Leadership",
    desc: "Skilled in leading and managing development teams, fostering collaboration and efficiency across cross-functional projects.",
  },
  {
    icon: "🗄️",
    title: "Database Management",
    desc: "Proficient in MySQL and Oracle databases with deep experience in API integration for robust, scalable data solutions.",
  },
  {
    icon: "🔍",
    title: "Debugging & Optimization",
    desc: "Experienced in debugging high-performance business applications to ensure seamless, reliable operation under production loads.",
  },
];
 
const experience = [
  {
    role: "Assistant Manager — Web Application",
    company: "Atlas Honda Limited",
    period: "December 2025 – Present · 4 months",
    desc: "Applying keen observation and in-depth analysis to support tailored IT solutions, enabling businesses through ERP systems and ensuring effective stakeholder collaboration.",
  },
  {
    role: "Senior ERP Developer PHP",
    company: "DE Solutions",
    period: "March 2024 – December 2025 · 1 year 10 months",
    desc: "Senior-level ERP development and customization in PHP, handling high-performance business application modules and API integrations for enterprise clients.",
  },
  {
    role: "Senior PHP Developer",
    company: "ARWAJ TECH",
    period: "October 2022 – July 2023 · 10 months",
    desc: "Full-stack PHP development with a focus on building scalable web applications and integrating third-party services.",
  },
  {
    role: "Development Team Lead",
    company: "DYS Solutions (Pvt.) Ltd",
    period: "May 2021 – March 2022 · 11 months",
    desc: "Led the development team, managing sprint planning, code reviews, and delivery timelines while fostering a collaborative engineering culture.",
  },
  {
    role: "Senior ERP / PHP Developer",
    company: "DYS Solutions (Pvt.) Ltd",
    period: "April 2017 – May 2021 · 4 years 2 months",
    desc: "Built and maintained a PHP-based ERP product covering all core modules — Sales, Purchase, General Ledger, Inventory, POS, and CRM.",
  },
  {
    role: "Intern",
    company: "PTCL",
    period: "June 2015 – July 2015 · 2 months",
    desc: null,
  },
];
 
const education = [
  {
    year: "2013 – 2016",
    degree: "Bachelor of Engineering — Telecommunications",
    school: "NED University of Engineering and Technology",
  },
  {
    year: "2011 – 2012",
    degree: "Intermediate — Pre-Engineering",
    school: "BAMM P.E.C.H.S College for Women",
  },
  {
    year: "1998 – 2010",
    degree: "Matriculation — Computer Science",
    school: "Federal Secondary School",
  },
];
 
function useInView(threshold = 0.15) {
  const ref = useRef(null);
  const [visible, setVisible] = useState(false);
  useEffect(() => {
    const obs = new IntersectionObserver(
      ([entry]) => { if (entry.isIntersecting) setVisible(true); },
      { threshold }
    );
    if (ref.current) obs.observe(ref.current);
    return () => obs.disconnect();
  }, []);
  return [ref, visible];
}
 
function SkillBar({ name, pct, delay }) {
  const [ref, visible] = useInView();
  return (
    <div ref={ref} style={{ marginBottom: 24 }}>
      <div style={{ display: "flex", justifyContent: "space-between", marginBottom: 6 }}>
        <span style={{ fontSize: 13, color: COLORS.white }}>{name}</span>
        <span style={{ fontSize: 12, color: COLORS.accent }}>{pct}%</span>
      </div>
      <div style={{ height: 2, background: COLORS.border, position: "relative" }}>
        <div
          style={{
            position: "absolute", top: 0, left: 0, height: "100%",
            background: `linear-gradient(90deg, ${COLORS.accent}, ${COLORS.accent2})`,
            width: visible ? `${pct}%` : "0%",
            transition: `width 1s ease ${delay}ms`,
          }}
        />
      </div>
    </div>
  );
}
 
function SectionHeader({ label, num }) {
  return (
    <div style={{
      display: "flex", justifyContent: "space-between", alignItems: "center",
      padding: "20px 48px", borderBottom: `1px solid ${COLORS.border}`,
    }}>
      <span style={{ fontSize: 11, letterSpacing: "0.2em", textTransform: "uppercase", color: COLORS.muted }}>
        {label}
      </span>
      <span style={{ fontFamily: "Syne, sans-serif", fontSize: 14, color: COLORS.border }}>
        {num}
      </span>
    </div>
  );
}
 
function NavBar({ active, setActive }) {
  const links = ["Summary", "Expertise", "Skills", "Experience", "Education", "Contact"];
  return (
    <nav style={{
      position: "sticky", top: 0, zIndex: 100,
      display: "flex", justifyContent: "space-between", alignItems: "center",
      padding: "16px 48px",
      background: "rgba(12,12,15,0.92)",
      backdropFilter: "blur(12px)",
      borderBottom: `1px solid ${COLORS.border}`,
    }}>
      <div style={{
        fontFamily: "Syne, sans-serif", fontWeight: 800, fontSize: 15,
        background: `linear-gradient(90deg, ${COLORS.accent}, ${COLORS.accent2})`,
        WebkitBackgroundClip: "text", WebkitTextFillColor: "transparent",
      }}>
        Ramsha Ather
      </div>
      <div style={{ display: "flex", gap: 28 }}>
        {links.map(l => (
          <a
            key={l}
            href={`#${l.toLowerCase()}`}
            onClick={() => setActive(l)}
            style={{
              fontSize: 11, letterSpacing: "0.12em", textTransform: "uppercase",
              color: active === l ? COLORS.accent : COLORS.muted,
              textDecoration: "none", transition: "color 0.2s",
            }}
          >
            {l}
          </a>
        ))}
      </div>
      <div style={{
        fontSize: 10, letterSpacing: "0.12em", textTransform: "uppercase",
        padding: "5px 14px", border: `1px solid ${COLORS.accent3}`,
        color: COLORS.accent3, borderRadius: 999,
      }}>
        Open to Work
      </div>
    </nav>
  );
}
 
function Hero() {
  const pills = ["PHP", "Laravel", "CodeIgniter", "Oracle Apex", "MySQL", "ERP", "API Integration", "Git", "Linux"];
  return (
    <section id="hero" style={{
      minHeight: "100vh", display: "flex", flexDirection: "column",
      justifyContent: "center", padding: "80px 48px 64px",
      borderBottom: `1px solid ${COLORS.border}`, position: "relative", overflow: "hidden",
    }}>
      <div style={{
        position: "absolute", inset: 0, pointerEvents: "none",
        background: `radial-gradient(ellipse 60% 50% at 80% 50%, rgba(192,132,252,0.07) 0%, transparent 70%),
                     radial-gradient(ellipse 40% 40% at 20% 80%, rgba(129,140,248,0.06) 0%, transparent 70%)`,
      }} />
      <div style={{
        position: "absolute", inset: 0, pointerEvents: "none",
        backgroundImage: "radial-gradient(circle, rgba(255,255,255,0.025) 1px, transparent 1px)",
        backgroundSize: "32px 32px",
      }} />
 
      <div style={{ position: "relative", zIndex: 1, maxWidth: 900 }}>
        <div style={{
          display: "flex", alignItems: "center", gap: 12,
          fontSize: 11, letterSpacing: "0.2em", textTransform: "uppercase",
          color: COLORS.accent, marginBottom: 24,
          animation: "fadeUp 0.6s ease both",
        }}>
          <span style={{ width: 32, height: 1, background: COLORS.accent, display: "block" }} />
          Senior PHP Developer
        </div>
 
        <h1 style={{
          fontFamily: "Syne, sans-serif", fontWeight: 800,
          fontSize: "clamp(3.5rem, 8vw, 7rem)",
          lineHeight: 0.92, letterSpacing: "-3px", margin: "0 0 16px",
          animation: "fadeUp 0.6s 0.12s ease both",
        }}>
          Ramsha
          <span style={{ display: "block", color: COLORS.accent }}>Ather</span>
        </h1>
 
        <p style={{
          fontSize: 13, color: COLORS.muted, marginBottom: 28,
          lineHeight: 1.9, maxWidth: 620,
          animation: "fadeUp 0.6s 0.24s ease both",
        }}>
          <span style={{ color: COLORS.accent2 }}>Team Lead · ERP Developer · PHP Core · Laravel · CodeIgniter</span>
          <br />Oracle Apex · API Integration · MySQL · Linux
        </p>
 
        <div style={{
          display: "flex", flexWrap: "wrap", gap: 8, marginBottom: 36,
          animation: "fadeUp 0.6s 0.36s ease both",
        }}>
          {pills.map(p => (
            <span key={p} style={{
              fontSize: 10, letterSpacing: "0.1em", textTransform: "uppercase",
              padding: "5px 14px", border: `1px solid ${COLORS.border}`,
              color: COLORS.muted, borderRadius: 999,
            }}>{p}</span>
          ))}
        </div>
 
        <div style={{
          display: "flex", gap: 14, flexWrap: "wrap",
          animation: "fadeUp 0.6s 0.48s ease both",
        }}>
          <a href="mailto:ramsha_ather@hotmail.com" style={btnStyle("primary")}>Email Me</a>
          <a href="https://www.linkedin.com/in/ramsha-ather-67219a105" target="_blank" rel="noreferrer" style={btnStyle("secondary")}>LinkedIn</a>
        </div>
      </div>
 
      <div style={{
        position: "absolute", right: 48, bottom: 48, zIndex: 1,
        display: "flex", gap: 36,
        animation: "fadeUp 0.6s 0.6s ease both",
      }}>
        {[["7+", "Years Exp"], ["6", "Companies"], ["10+", "ERP Modules"]].map(([n, l]) => (
          <div key={l} style={{ textAlign: "right" }}>
            <div style={{ fontFamily: "Syne, sans-serif", fontWeight: 800, fontSize: 40, color: COLORS.accent, lineHeight: 1 }}>{n}</div>
            <div style={{ fontSize: 10, letterSpacing: "0.12em", textTransform: "uppercase", color: COLORS.muted }}>{l}</div>
          </div>
        ))}
      </div>
 
      <style>{`
        @keyframes fadeUp {
          from { opacity: 0; transform: translateY(16px); }
          to   { opacity: 1; transform: translateY(0); }
        }
      `}</style>
    </section>
  );
}
 
function btnStyle(type) {
  const base = {
    fontFamily: "Space Mono, monospace", fontSize: 11,
    letterSpacing: "0.1em", textTransform: "uppercase",
    padding: "13px 28px", cursor: "pointer", textDecoration: "none",
    border: "1px solid", display: "inline-block",
    transition: "all 0.2s",
  };
  if (type === "primary") return { ...base, background: COLORS.accent, color: "#0c0c0f", borderColor: COLORS.accent };
  return { ...base, background: "transparent", color: COLORS.white, borderColor: COLORS.border };
}
 
function Summary() {
  return (
    <section id="summary" style={{ borderBottom: `1px solid ${COLORS.border}` }}>
      <SectionHeader label="Summary" num="01" />
      <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr" }}>
        <div style={{ padding: "56px 48px", borderRight: `1px solid ${COLORS.border}` }}>
          <blockquote style={{
            fontFamily: "Syne, sans-serif", fontSize: "clamp(1.3rem, 2.5vw, 1.9rem)",
            fontWeight: 700, lineHeight: 1.3, letterSpacing: "-0.5px", margin: 0,
          }}>
            Enabling businesses through{" "}
            <span style={{
              background: `linear-gradient(90deg, ${COLORS.accent}, ${COLORS.accent2})`,
              WebkitBackgroundClip: "text", WebkitTextFillColor: "transparent",
            }}>ERP systems</span>{" "}
            with over seven years of high-impact development experience.
          </blockquote>
        </div>
        <div style={{ padding: "56px 48px" }}>
          {[
            "With over seven years of experience in ERP and PHP development, I bring expertise in creating, customizing, and debugging high-performance business applications.",
            "My work has spanned critical modules such as Sales, Purchase, General Ledger, Inventory, POS, and CRM — alongside robust API integration.",
            "Currently serving as Assistant Manager – Web Application at Atlas Honda Limited, I apply keen observation and in-depth analysis to support tailored IT solutions, ensuring streamlined processes and effective stakeholder collaboration.",
          ].map((p, i) => (
            <p key={i} style={{ fontSize: 13, color: COLORS.muted, lineHeight: 1.9, marginBottom: i < 2 ? 14 : 0 }}>{p}</p>
          ))}
        </div>
      </div>
    </section>
  );
}
 
function Expertise() {
  return (
    <section id="expertise" style={{ borderBottom: `1px solid ${COLORS.border}` }}>
      <SectionHeader label="Key Expertise" num="02" />
      <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr" }}>
        {expertise.map((e, i) => (
          <div key={i} style={{
            padding: "40px 48px",
            borderRight: i % 2 === 0 ? `1px solid ${COLORS.border}` : "none",
            borderBottom: i < 2 ? `1px solid ${COLORS.border}` : "none",
            transition: "background 0.3s", cursor: "default",
          }}
            onMouseEnter={ev => ev.currentTarget.style.background = COLORS.surface}
            onMouseLeave={ev => ev.currentTarget.style.background = "transparent"}
          >
            <div style={{
              fontSize: 20, marginBottom: 20, width: 44, height: 44,
              display: "flex", alignItems: "center", justifyContent: "center",
              border: `1px solid ${COLORS.border}`, borderRadius: 8, background: COLORS.surface,
            }}>{e.icon}</div>
            <h3 style={{ fontFamily: "Syne, sans-serif", fontSize: 17, fontWeight: 700, marginBottom: 10, letterSpacing: "-0.3px" }}>{e.title}</h3>
            <p style={{ fontSize: 13, color: COLORS.muted, lineHeight: 1.8 }}>{e.desc}</p>
          </div>
        ))}
      </div>
    </section>
  );
}
 
function Skills() {
  return (
    <section id="skills" style={{ borderBottom: `1px solid ${COLORS.border}` }}>
      <SectionHeader label="Top Skills" num="03" />
      <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr" }}>
        <div style={{ padding: "48px", borderRight: `1px solid ${COLORS.border}` }}>
          <p style={{ fontSize: 11, letterSpacing: "0.2em", textTransform: "uppercase", color: COLORS.muted, marginBottom: 28 }}>Proficiency</p>
          {skills.map((s, i) => <SkillBar key={s.name} name={s.name} pct={s.pct} delay={i * 80} />)}
        </div>
        <div style={{ padding: "48px" }}>
          <p style={{ fontSize: 11, letterSpacing: "0.2em", textTransform: "uppercase", color: COLORS.muted, marginBottom: 28 }}>Technology Tags</p>
          <div style={{ display: "flex", flexWrap: "wrap", gap: 8 }}>
            {tags.map(t => (
              <span key={t.label} style={{
                fontSize: 11, letterSpacing: "0.08em",
                padding: "7px 14px", border: `1px solid ${t.hl ? COLORS.accent : COLORS.border}`,
                color: t.hl ? COLORS.accent : COLORS.muted,
                transition: "all 0.2s", cursor: "default",
              }}>{t.label}</span>
            ))}
          </div>
        </div>
      </div>
    </section>
  );
}
 
function Experience() {
  return (
    <section id="experience" style={{ borderBottom: `1px solid ${COLORS.border}` }}>
      <SectionHeader label="Professional Experience" num="04" />
      <div style={{ padding: "48px" }}>
        {experience.map((e, i) => (
          <div key={i} style={{ display: "grid", gridTemplateColumns: "40px 1fr", gap: 24, paddingBottom: i < experience.length - 1 ? 40 : 0 }}>
            <div style={{ display: "flex", flexDirection: "column", alignItems: "center" }}>
              <div style={{
                width: 10, height: 10, borderRadius: "50%",
                background: COLORS.accent, border: `2px solid ${COLORS.bg}`,
                outline: `1px solid ${COLORS.accent}`, flexShrink: 0, marginTop: 5,
              }} />
              {i < experience.length - 1 && (
                <div style={{ width: 1, flex: 1, background: COLORS.border, marginTop: 6 }} />
              )}
            </div>
            <div>
              <div style={{ fontFamily: "Syne, sans-serif", fontSize: 16, fontWeight: 700, marginBottom: 4, letterSpacing: "-0.3px" }}>{e.role}</div>
              <div style={{ fontSize: 13, color: COLORS.accent2, marginBottom: 4 }}>{e.company}</div>
              <div style={{ fontSize: 11, color: COLORS.muted, letterSpacing: "0.05em" }}>{e.period}</div>
              {e.desc && <p style={{ fontSize: 13, color: COLORS.muted, marginTop: 10, lineHeight: 1.8 }}>{e.desc}</p>}
            </div>
          </div>
        ))}
      </div>
    </section>
  );
}
 
function Education() {
  return (
    <section id="education" style={{ borderBottom: `1px solid ${COLORS.border}` }}>
      <SectionHeader label="Education" num="05" />
      <div style={{ display: "grid", gridTemplateColumns: "repeat(3, 1fr)" }}>
        {education.map((e, i) => (
          <div key={i} style={{
            padding: "40px 32px",
            borderRight: i < 2 ? `1px solid ${COLORS.border}` : "none",
            transition: "background 0.3s",
          }}
            onMouseEnter={ev => ev.currentTarget.style.background = COLORS.surface}
            onMouseLeave={ev => ev.currentTarget.style.background = "transparent"}
          >
            <div style={{ fontSize: 10, letterSpacing: "0.12em", textTransform: "uppercase", color: COLORS.accent, marginBottom: 14 }}>{e.year}</div>
            <div style={{ fontFamily: "Syne, sans-serif", fontSize: 15, fontWeight: 700, lineHeight: 1.3, marginBottom: 8, letterSpacing: "-0.2px" }}>{e.degree}</div>
            <div style={{ fontSize: 13, color: COLORS.muted, lineHeight: 1.7 }}>{e.school}</div>
          </div>
        ))}
      </div>
    </section>
  );
}
 
function Contact() {
  return (
    <section id="contact" style={{ borderBottom: `1px solid ${COLORS.border}` }}>
      <SectionHeader label="Get in Touch" num="06" />
      <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr" }}>
        <div style={{ padding: "56px 48px", borderRight: `1px solid ${COLORS.border}` }}>
          <h2 style={{
            fontFamily: "Syne, sans-serif", fontWeight: 800,
            fontSize: "clamp(2rem, 4vw, 3.5rem)",
            lineHeight: 0.95, letterSpacing: "-2px", marginBottom: 24,
          }}>
            Let's build <span style={{ color: COLORS.accent }}>something</span> great.
          </h2>
          <p style={{ fontSize: 13, color: COLORS.muted, lineHeight: 1.9, maxWidth: 360 }}>
            I'm always open to discussing new opportunities, interesting ERP challenges, or how I can contribute to your engineering team. Feel free to reach out anytime.
          </p>
        </div>
        <div style={{ padding: "56px 48px", display: "flex", flexDirection: "column", justifyContent: "center" }}>
          {[
            { label: "Email", detail: "ramsha_ather@hotmail.com →", href: "mailto:ramsha_ather@hotmail.com" },
            { label: "LinkedIn", detail: "ramsha-ather →", href: "https://www.linkedin.com/in/ramsha-ather-67219a105" },
            { label: "Languages", detail: "English · Urdu →", href: "#" },
          ].map((item, i) => (
            <div key={i} style={{ borderBottom: `1px solid ${COLORS.border}`, borderTop: i === 0 ? `1px solid ${COLORS.border}` : "none" }}>
              <a href={item.href} target={item.href.startsWith("http") ? "_blank" : undefined} rel="noreferrer" style={{
                display: "flex", justifyContent: "space-between", alignItems: "center",
                padding: "22px 0", color: COLORS.white, textDecoration: "none",
                fontSize: 14, transition: "color 0.2s",
              }}
                onMouseEnter={ev => ev.currentTarget.style.color = COLORS.accent}
                onMouseLeave={ev => ev.currentTarget.style.color = COLORS.white}
              >
                <span>{item.label}</span>
                <span style={{ fontSize: 12, color: COLORS.muted }}>{item.detail}</span>
              </a>
            </div>
          ))}
        </div>
      </div>
    </section>
  );
}
 
export default function RamshaPortfolio() {
  const [active, setActive] = useState("Summary");
 
  useEffect(() => {
    const link1 = document.createElement("link");
    link1.rel = "stylesheet";
    link1.href = "https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Syne:wght@400;600;700;800&display=swap";
    document.head.appendChild(link1);
  }, []);
 
  return (
    <div style={{
      background: COLORS.bg, color: COLORS.white,
      fontFamily: "Space Mono, monospace", lineHeight: 1.6, minHeight: "100vh",
    }}>
      <NavBar active={active} setActive={setActive} />
      <Hero />
      <Summary />
      <Expertise />
      <Skills />
      <Experience />
      <Education />
      <Contact />
      <footer style={{
        padding: "24px 48px", display: "flex", justifyContent: "space-between", alignItems: "center",
        borderTop: `1px solid ${COLORS.border}`,
      }}>
        <span style={{ fontSize: 11, color: COLORS.muted }}>© 2026 Ramsha Ather. All rights reserved.</span>
        <span style={{ fontSize: 11, color: COLORS.muted }}>Senior PHP Developer · Karachi, Pakistan</span>
      </footer>
    </div>
  );
}
