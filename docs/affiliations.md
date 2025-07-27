---
sidebar_position: 2
---

# Affiliations

<div
  style={{
    display: 'grid',
    gridTemplateColumns: 'repeat(4, 1fr)',
    gap: '1.5rem',
    marginTop: '1.5rem'
  }}
>
  {[
    {
      img: '/website/img/ncor.png',
      title: 'National Center for Ontological Research (NCOR)',
      role: 'NCOR Director',
      url: 'https://ncor.us',
    },
    {
      img: '/website/img/ub.png',
      title: 'University at Buffalo Department of Philosophy',
      role: 'SUNY Distinguished Professor of Philosophy, Julian Park Chair',
      url: 'https://www.buffalo.edu/cas/philosophy/faculty/faculty_directory/smith-b.html',
    },
    {
      img: '/website/img/jacobs.png',
      title: 'University at Buffalo Jacobs School of Medicine and Biomedical Sciences',
      role: 'Professor',
      url: 'https://medicine.buffalo.edu/faculty/profile.html?ubit=phismith',
    },
    {
      img: '/website/img/computer.jpg',
      title: 'University at Buffalo Department of Computer Science and Engineering',
      role: 'Professor',
      url: 'https://engineering.buffalo.edu/computer-science-engineering/people/faculty-directory.host.html/content/shared/cas/philosophy/faculty-profiles/smith.html',
    },
    {
      img: '/website/img/romanell.jpg',
      title: 'University at Buffalo Romanell Center for Clinical Ethics and the Philosophy of Medicine',
      role: 'Member',
      url: 'https://www.buffalo.edu/romanell/people/smith.html',
    },
    {
      img: '/website/img/ifomis.png',
      title: 'Institute for Formal Ontology and Medical Information Science (IFOMIS) at Saarland University',
      role: 'Founding Director',
      url: 'https://www.uni-saarland.de/institut/ifomis.html',
    },
    {
      img: '/website/img/acmi.jpg',
      title: 'American College of Medical Informatics',
      role: 'Fellow',
      url: 'https://amia.org/membership/barry-smith-phd-facmi',
    },
    {
      img: '/website/img/obo.png',
      title: 'OBO Foundry',
      role: 'OBO Operations Committee Membership',
      url: 'https://obofoundry.org/docs/Membership.html',
    },
    {
      img: '/website/img/ontocommons.png',
      title: 'Onto Commons',
      role: 'External Advisory Board',
      url: 'https://ontocommons.eu/eag/barry-smith-0',
    },
  ].map((item) => (
    <div
      key={item.title}
      style={{
        display: 'flex',
        flexDirection: 'column',
        alignItems: 'center',
        textAlign: 'center',
        padding: '1rem',
        boxSizing: 'border-box',
      }}
    >
      <img
        src={item.img}
        alt={item.title}
        style={{
          maxWidth: '100px',
          height: '100px',   // Fix height to align images
          objectFit: 'contain',
          marginBottom: '1rem',
        }}
      />
      <h4
        style={{
          minHeight: '3em',  // fix title height for alignment
          margin: '0 0 0.5rem 0',
          lineHeight: '1.2em',
          display: 'flex',
          alignItems: 'center',
          justifyContent: 'center',
        }}
      >
        <a href={item.url} target="_blank" rel="noopener noreferrer">
          {item.title}
        </a>
      </h4>
      <p style={{ fontSize: '0.9rem', color: '#444', margin: 0 }}>{item.role}</p>
    </div>
  ))}
</div>
