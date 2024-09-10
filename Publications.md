# Define a list of dictionaries for the publications
publications = [
    {
        "title": "Carbon Supports Mitigate Resistivity Limitations in Ni–Mo Alkaline Hydrogen Evolution Electrocatalysts",
        "authors": "Patil, R.B.; Mantri, A.; House, S.; Yang, J.; McKone, J.R.",
        "year": "In Review",
        "link": "https://doi.org/10.26434/chemrxiv.7037264"
    },
    {
        "title": "Flow Battery Electroanalysis 2: Influence of Surface Pretreatment on Fe(III/II) Redox Chemistry at Carbon Electrodes",
        "authors": "Sawant, T.; McKone, J.R.",
        "year": "2019",
        "link": "#"
    },
    {
        "title": "Flow Battery Electroanalysis: Hydrodynamic Voltammetry of Aqueous Fe(III/II) Redox Couples at Polycrystalline Pt and Au",
        "authors": "Sawant, T.; McKone, J.R.",
        "year": "2018",
        "link": "#"
    },
    {
        "title": "Elucidating the Active Sites for CO2 Electroreduction on Ligand-Protected Au25 Nanoclusters",
        "authors": "Austin, N.; Zhao, S.; McKone, J.; Jin, R.; Mpourmpakis, G.",
        "year": "2018",
        "link": "#"
    },
    {
        "title": "Solar Energy Conversion, Storage, and Release Using an Integrated Solar-Driven Redox Flow Battery",
        "authors": "McKone, J.R., DiSalvo, F.J., Abruña, H.D.",
        "year": "2017",
        "link": "https://doi.org/10.1039/C7TA00555E"
    },
    {
        "title": "Electrochemical Hydrogen Evolution at Ordered Mo7Ni7",
        "authors": "Csernica, P.M.; McKone, J.R.; Abruña, H.D.; DiSalvo, F.J.",
        "year": "2017",
        "link": "https://doi.org/10.1021/acscatal.7b00344"
    },
    {
        "title": "Superior Charge Storage and Power Density of a Conducting Polymer-Modified Covalent Organic Framework",
        "authors": "Mulzer, C. R.; Shen, L.; Bisbey, R.P.; McKone, J.R.; Zhang, N.; Abruña, H.D.; Dichtel, W.R.",
        "year": "2016",
        "link": "https://doi.org/10.1021/acscentsci.6b00220"
    },
    {
        "title": "Translational Science for Energy and Beyond",
        "authors": "McKone, J. R.; Crans, D.; Martin, C.; Turner, J.; Duggal, A.R.; Gray, H.G.",
        "year": "2016",
        "link": "https://doi.org/10.1021/acs.inorgchem.6b01097"
    },
    {
        "title": "On the Benefits of a Symmetric Redox Flow Battery",
        "authors": "Potash, R. A.; McKone, J. R.; Abruña, H. D.",
        "year": "2016",
        "link": "https://doi.org/10.1149/2.0971602jes"
    },
    {
        "title": "Thin-Film Materials for the Protection of Semiconducting Photoelectrodes in Solar-Fuels Generators",
        "authors": "Hu, S.; Lewis, N. S.; Ager, J. W.; Yang, J.; McKone, J. R.; Strandwitz, N. C.",
        "year": "2015",
        "link": "https://doi.org/10.1021/acs.jpcc.5b05976"
    }
]

# Create the Markdown content for publications
with open('publications.md', 'w') as file:
    file.write("---\n")
    file.write("layout: page\n")
    file.write("title: Publications\n")
    file.write("permalink: /publications/\n")
    file.write("---\n\n")
    file.write("## Publications\n\n")
    
    for i, pub in enumerate(publications, start=1):
        file.write(f"{i}. **{pub['title']}**\n")
        file.write(f"   _Authors:_ {pub['authors']}\n")
        file.write(f"   _Year:_ {pub['year']}\n")
        file.write(f"   [{pub['link']}]\n\n")

print("Markdown file 'publications.md' created successfully!")
