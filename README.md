# Open-Source-Wearables

This project is meant to act as an open library of wearable components, techniques, or research related to wearing technology. This is a personal repository that I am using to organize my thoughts, but I want for my work to be used and built upon. Choose MIT or Apache2 for licensing and just attribute Pipeargill if you find anything useful in your project.  

![20241205_011319](https://github.com/user-attachments/assets/335df770-ff78-4379-9a01-515f40939c54)


### Project Overview  

The first goal of this project is to develop a modular wearable system starting with the 3M 6000 Series Respirator Masks.  

![20241205_002423](https://github.com/user-attachments/assets/14851dcb-9b65-45dc-87be-e97fc3cf0171)

Respirator masks offer a versatile platform for building cosplay helmets and fursuit heads because they can be attched to easily, fit securely, and come with useful benefits..like filtering air. I’ve discovered that wearing a respirator mask, especially for seasonal allergies, is not only more comfortable than taking allergy medications but gives me an awesome opportunity for expression.

![20241205_002525](https://github.com/user-attachments/assets/dd5dd993-fc13-41a3-9461-2a94155eefbc)

The respirator masks are relitively affordable, fairly comfortable, feature an anti-fog exhaust port, and have adjustable straps that can easily be replaced. The aim of this project is to create modular adapters and accessories that allow the creation of custom cosplay, fursuit, cyberwear, or prosthesis designs that can be easily attached to the mask.

---

## Cyberwear  
This category is for functional parts that add to a wearable's functionality or act as some sort of usability aid or prosthesis. Think anything from lights and sounds to radio or computer systems.

## Cosplay  
This category is for parts and techniques related to turning 3D designs into wearables. Think hard shell armor and character faces printed directly.

![20241222_000936](https://github.com/user-attachments/assets/88ed588a-4be1-47ab-a428-a49742275959)

## Fursuit  
This category is for parts and techniques related to turning character concepts into wearables that utilize a fabric, textile, or faux-fur outer layer.

## Utility/Tactical
This category is for anything that has a specific functon as a tool that doesn't fall neatly into cyberwear or anything designed to be defensive such as armor.

## Solutions
This category is a catch-all for components that adapt one thing to another, hold a thing in a place, or otherwise solve a problem or adapt one category into another.

## Toolbox  
This category is for relief cuts or other tools.

---

### Current Development  

I am currently working on 3D modeling adapters that allow the respirator mask to be attached. I have one adapter almost ready for beta and a few more in development. The long-term goal is to make the system modular to allow users to easily swap parts based on their design needs or to easily relief cut their own 3D design into a compatible part for this system.  

#### Remote Air Supply  

Adapter set almost ready for beta!
v0.3 12/24/24

The first use case will be fitting the mask under my MTB full face helmet and attaching the remote filters somewhere. I've already test fitted the 3M half mask respirator under the helmet with the low profile adapters, I just need to film and document and do all the publishing junk.

These adapters seem expensive for no good reason.  

![449N09_AS01](https://github.com/user-attachments/assets/0ae01796-2914-4c70-8d7e-cb7c2137baa8)


This is a low-profile adapter to allow air supply connections that can fit under a mask. I am considering it a Solutions part and it will be a base component for many other designs that will fall into other categories. It attaches to 5 0.25in/7mm rubber hoses and connects to the corresponding part that holds the filter. This opens to opportunity to inject oxygen or various medications into the airstream and could help those with breathing complications, especially in active settings.

#### S-1 Beta 0.4 beta

![20241220_141300](https://github.com/user-attachments/assets/645a9185-50a4-4293-a1ff-043a1e5d5381)

I have designed the corresponding part that will connect to the filter and allow for remote placement, just need to document and publish.

---

## Research into molecular geomety

After seeing Crash Makerspace's video on using resin 3D printed structures, I started really thinking about this problem in my idle time.  I read comments by @erokfussell that go back and forth a bit with @CrashMakerspace and decided to try to understand more about these structures. I really appreciated this video for explaining the concepts in a way that was approachable to the way I understand materials and force and I appreciate the scientific approach and willingness to share knowledge.

[Making 3D Prints Bulletproof with Molecular Structures - CrashMakerspace](https://youtu.be/G6AaAU4Sv5w?si=gatsVJPxFeBfWkmN)

![Screenshot_20241212-212144_YouTube](https://github.com/user-attachments/assets/769a7fb0-ccc2-41ae-ad55-5a3ad2c9dec1)
![Screenshot_20241212-212220_YouTube](https://github.com/user-attachments/assets/c0d60d8b-98d3-469e-a9c1-ea9fb94e256f)
![Screenshot_20241212-212231_YouTube](https://github.com/user-attachments/assets/dd590a01-fbf5-447a-bd85-6517e98ff8ee)
![Screenshot_20241212-212238_YouTube](https://github.com/user-attachments/assets/dc4c9a95-d3da-444a-af0e-10be83821ae9)

I looked around a bit and found a model that was very interesting because it was a lattus structure nested within another lattus structure. [Duble-Diamond mutual structure - Bulagen](https://www.myminifactory.com/object/3d-print-duble-diamond-mutual-structure-17925)

Here is a spacing experiment I tried using this structure as a guide.

<img width="249" alt="Capture9" src="https://github.com/user-attachments/assets/b5bfac85-b21c-4c57-b45a-6b9b0582bfde" />

The idea of a double lattuce structure is interesting because it could allow for nodes of the lattuce to be less effected for the rapidly moving shockwave that travels through the material, or by varying the size of the tabs that connect lattuce A to lattuce B while nested togeather, the force could be redirected into "unzipping" the 2 structures. This is purely conjecture and I am probably not going to test printed copies of these structures at this point. I've found it challenging to work with this sort of structure in Fusion 360 but I like that and I may approach this again once I have more than 12GB of RAM and everything stops freezing.
<img width="641" alt="Capturelol" src="https://github.com/user-attachments/assets/12dedeb5-09c7-420a-8fab-fd41bb4fd8f1" />

Here is a layout of how I was attempting to pattern the nodes out of bodies after generating a lattus structure.

<img width="444" alt="Capture2" src="https://github.com/user-attachments/assets/2a40bbd6-1e6c-4f63-895e-33c03a404eec" />
<img width="442" alt="Capture3" src="https://github.com/user-attachments/assets/679f07e5-4cc0-4558-91c8-fbb4e7ca111f" />
<img width="455" alt="Capture4" src="https://github.com/user-attachments/assets/80e6c019-0ade-492f-b898-6b11bdd482d4" />
<img width="354" alt="Capture5" src="https://github.com/user-attachments/assets/9257950b-7af0-4b95-8736-e47a26398327" />
<img width="511" alt="Capture6" src="https://github.com/user-attachments/assets/a419f0ee-e92a-4012-95d5-aa5dedaee3d7" />
<img width="482" alt="Capture7" src="https://github.com/user-attachments/assets/95d01eb5-0f64-474c-b6de-e284670dc0cd" />
<img width="517" alt="Capture8" src="https://github.com/user-attachments/assets/841333a9-ae70-486c-9809-6547d4c86b42" />

Here is an example of how these structures can nest

<img width="442" alt="Double" src="https://github.com/user-attachments/assets/32d2a1b8-09c1-413c-8f9f-1a991ea04919" />

Another view, from here you can see some space because the nesting I manually arranged isn't centered.

<img width="497" alt="Capture44" src="https://github.com/user-attachments/assets/660b4ba5-66cb-4c43-a3bd-34da4bb097f0" />

Tripple nested, these nodes are very close togeather

<img width="494" alt="tripple" src="https://github.com/user-attachments/assets/b7806749-0742-48ff-ad15-99883f388e0d" />

One last video I want to leave this idea with that could be useful because it showcases several structures, I'm unfamilure with this software otherwise:
[What is lattice structure - Innogrit 3D](https://youtube.com/shorts/OYSQpLlBmEs?si=5Nqu5sfW5F0YzJVN)


*1 I am including my STEP files for this research under MIT or Apache2, the only thing close to an origional idea here is my idea of utalizing a double nested molecular diamond structure in balistic testing. This idea remains unproven.

*2 I utalized CrashMakerspace's 20mm resin print file purely for research purposes by getting a general scale for the structures being worked with. Their IP is their own and I am not redistributing those files.

*3 Duble-Diamond mutual structure by Bulagen is Licensed MyMiniFactory - Credit - Remix - Noncommercial
I am including a copy in one of my files as refrence, this copy is unaltered and not attached physically or by symbolic relationship to any other objects in that file and should not change the MIT or Apache2 status of the other objects in that file, which I own and share under MIT or Apache2. I am not a lawyer.

---

### Next Actions

- **Set up publishing channels and website**

- **Set up camera and studio to document work so far**

- **Research 3M mask with speaking diaphragm**
![Disloyal_man_with_his_girlfriend_looking_at_another_girl](https://github.com/user-attachments/assets/35620ef0-ed29-4420-a334-201cd1b2435d)
![3M-Secure-Click-Half-Facepiece-Reusable-Respirator-HF-800-Series](https://github.com/user-attachments/assets/846e6f65-37c0-4b78-bad8-4531ee587d22)

- **Documentation on 18v power supply**: I utilize Ridgid 18v drill packs because they have a low voltage cutoff that is useful. I don't recommend DeWalt 20v batteries without a controller board because they can be ran down to 0v.
I'm using adapter plates that I bought, but I can design out some printed ones that use male spade connections to interface with the batteries. I've found a 12/24v USB/C marine adapter that works great with 16-22v or whatever drillpacks are. There's also a neat 3A buck/boost converter that I've found that could also be useful.

- **Motorcycle/MTB Helmet Integration**: A version that works with a full-face helmet on top of a half mask.

- **Red Hood/Power Rangers/Kamen Rider helmet base**
This is a challenge I want to tackle early on as a way to push this design. It should be easy to fit a respirator mask under a big head, but I want to try to produce a very low profile design so that these sorts of helmets are possible. This will utilize the remote filter adapters I'm almost ready with.


### Future Ideas
  
- **Transhumanist Stillsuit**: With a focus on adapting to air quality concerns, this suit aims to normalize mask-wearing in everyday life with potential for oxygen or inhaler supply.
  
- **Mobility Support**: Features focused on user needs such as standing, walking, or wheelchair/mobility aid adapters. This is an idea that is a bit outside the current scope of the project, but my goal is to move to full body designs once the head design is mature enough to be modular.
  
- **Electronic Integrations**: Future designs will incorporate electronics like heads-up displays, lights, external displays, speakers, fans, ect.
  
- **Meshtastic/Radio**: Embedding comms systems.
  
- **Wide View Periscopes**: For TV head/Foreverwinter Shaman design cosplay. May end up doing a video feed, but I want to experiment with mirrors a bit here.

- **EDC holster**: Design holsters for every day carry items such as chapstick, tissues, knife, ect.
 (Cabela's Gentleman's EDC Knife)[https://www.basspro.com/shop/en/cabelas-gentleman-edc-folding-knife]
  
- **Dissect a used camera with a digital viewfinder for digital periscope**: Find common enough model
  
- **Space Marine/Zaku/Jin Roh Suit**: Focus on larger/bulky armored cosplay base.
- 
- **Tactical/Utilitarian Suit**: A base focused on practical use over form.
  
- **Ballistics**: Use of embedded printed structures that help resist bullet impacts—explore molecular geometries such as diamond, double diamond, graphene, and variations on these molecular structures in 3D printed resin.

- **TV Head Prince Robot IV**: TV head character that I plan to cosplay, which should make a good base design.

- **Puppet Head on Long Neck**: I want to try this as a way to add more articulation to a head that is puppeted on top of the user's head.  

---

### Log  


---
add bluesky posts
---



#### Proof of Concept - Test Print 1 (12/1/24)  

![20241201_193228](https://github.com/user-attachments/assets/7fa09887-2368-43ce-a3f5-a60393812566)  

**First Prototype Notes**  
The first prototype was a simple test design to see how the 3D print would attach to the exhaust port of the respirator mask.  

- **Prototype**: Horse skull adapter for 3M 6200 half-mask respirator.  
- **Objective**: Test fit, angle adjustment, and clearance.  
- **Result**: Mostly a failure, but it was able to be mounted and allowed me to measure how far I was off.  

---

### License & Usage  

This project is dual-licensed under the following:  
- [MIT License](licenses/MIT.txt)  
- [Apache License 2.0](licenses/Apache2.0.txt)  

You may choose either license to use this project.  

---

### Tiers of Access  
-**Pay What You Want**: I had originally planned to release some of my work for free and other parts as paid, but I have started to lean towards a donation model because I consider this project a type of activism. Please consider supporting my work if you are able to.

---

### Community & Open-Source Vision  

I hope to create a space where makers and designers can collaborate on wearable tech, cosplay, and cyberpunk gear. I welcome contributions, ideas, and variations from the community, as I believe this project can go in many exciting directions.  

Whether you’re a cosplayer or just someone who wants to breathe better, this project is meant to empower you to build unique creations that push the boundaries of wearable tech.  

---

### How to Contribute  

- **Feature Bounty**: If you want a feature developed, I am happy to help make that happen if I have time. My time is available for purchase if you'd like to commission a feature.  
- **Fork the Repository**: If you want to contribute designs, ideas, or feedback, feel free to fork the project and submit pull requests.  
- **Give Attribution**: If you use or modify the designs, please credit Pipeargill and this open-source project.  
- **Join a Tier Membership**: If you want to support the development of this project, consider joining a membership tier. Support will help fund the creation of new designs and prototypes, and I aim to make it worthwhile for my supporters.

### Philosophy & Goals

I am putting this at the end because it is both the most and least important part of this. Uncontrollable yapping follows:

Wearing a mask of any kind is unavoidably political in the United States and in many other places, so for many people simply protecting themselves and surviving in public is an act of resistance. 
This project is born out of a personal need to filter pollen while being active, particularly while mountain biking. My alergies are bad and medically relavent, but my needs are minor compaired to that of my friends and people I've known. The risk of losing the freedom to cover our face and protect our bodies is real and it is terrifying for the immunocompromised folk. 

United States prides itself on being a bastion of individual freedoms; however, recent mask bans exemplify a deep hypocrisy: the selective application of "freedom" depending on ideology. These bans, which prohibit individuals from wearing masks in public or at protests, contradict the values of personal liberty that many anti-mask advocates claimed to defend during the Covid-19 pandemic. This hypocrisy is not only harmful to public health but also endangers vulnerable populations, violates constitutional rights, and serves to suppress dissent.

Overview of Recent Mask Ban Legislation

1. New Mask Ban Proposals and Enforcements

New York Governor Kathy Hochul and other lawmakers are pushing for mask bans in protests, citing recent demonstrations over the Middle East crisis. The Nassau County Legislature has passed a law making it a crime to wear a mask or face covering in public to conceal identity, with similar measures adopted in North Carolina.

These laws often justify bans by claiming masked individuals engage in criminal behavior. For example, Nassau County's County Executive stated that police officers would assess the intent of masked individuals. Nassau County provides exceptions for medical and religious purposes, but enforcement remains ambiguous. Police have received minimal training (a five-slide presentation and a legal bulletin) to distinguish between legitimate and criminal uses of masks.

The inconsistency becomes clearer with examples like Florida Governor Ron DeSantis, who banned mask mandates in schools under the guise of protecting parental rights. Yet this action stripped parents of the freedom to decide whether their children could wear masks to school, especially in communities with high COVID-19 risks. Such policies betray the principle of freedom that anti-mask advocates supposedly championed, revealing that their fight was not for liberty, but for control.

2. Historical Context of Mask Bans

Mask laws historically served as performative gestures to distance states from overt racism (e.g., KKK violence) while maintaining systemic racist policies like segregation.

The first recorded mask ban in the United States dates back to New York in 1845, unrelated to the Ku Klux Klan (KKK). It targeted tenant farmers protesting exploitative landlord practices during the Anti-Rent War. Protesters disguised themselves with Native American masks to protect their identities.

Over time, mask bans evolved and were sporadically enforced, including against the KKK to deny marching permits and against protesters during the Occupy Wall Street movement in 2011. Despite their ostensible justification to combat hate groups, bans have largely been used to suppress protests.

Recent mask ban laws often include exceptions favoring organizations like the KKK such as allowing exemptions such as the use of hoods and when used as part of a secret societies' rituals, highlighting their performative and discriminatory nature of these bans.

3. Contradictions, Double Standards, and Selective Enforcement

Mask bans often reflect political hypocrisy. For instance, groups advocating for mask bans during protests are frequently the same factions that opposed public health mask mandates.

Anti-mask laws serve as tools for racial profiling and over-policing, disproportionately targeting marginalized communities.

Mask bans disproportionately harm vulnerable populations, particularly disabled and immunocompromised individuals. For these groups, masks are not a political statement but a critical health tool. The Centers for Disease Control and Prevention (CDC) estimates that 19% of American adults live with disabilities that increase their risk of severe illness from respiratory viruses (CDC). Forcing these individuals into public spaces without the ability to protect themselves violates their rights under the Americans with Disabilities Act (ADA). 

The moral argument is straightforward: protecting the rights of disabled people is protecting the rights of everyone. As the population ages, the number of people with disabilities will increase. Policies that disregard their needs set a dangerous precedent for society as a whole.

Mask bans embolden anti-mask sentiments and increase societal divisions. Harassment of mask-wearers (e.g., cancer patients) reflects a cultural hostility toward basic medical precautions.

The rollback of public health safeguards exacerbates risks for vulnerable populations while empowering police to enforce discriminatory practices.

Targeting Protests Under the Guise of Safety

GOP lawmakers in North Carolina explicitly linked their mask ban to protests at the University of North Carolina. Meanwhile, mask-wearing by right-wing groups like the Proud Boys at protests often goes unaddressed, underscoring a systemic double standard.

4. Mask Bans and the First Amendment

Mask bans also encroach upon First Amendment rights, particularly the right to anonymous expression. Historically, courts have upheld the right to mask-wearing as a form of political speech, such as during protests. In NAACP v. Alabama (1958), the Supreme Court recognized that anonymity is essential for individuals expressing dissenting views, especially in hostile environments. Despite this precedent, mask bans have been used to suppress protests, particularly those supporting marginalized groups.

Consider the current climate surrounding pro-Palestinian activism. Websites dedicated to doxxing activists, exposing their identities, and subjecting them to harassment have proliferated. Mask bans exacerbate this problem by forcing individuals to reveal their faces during demonstrations, leaving them vulnerable to retaliation. 

Face recognicion means that we are increasingly carrying our identifcation papers on our face, and banning masks at protests insures that the ability to protest without being doxxed and harassed will be vanishing. 
Privacy as a fundamental human right, recognized in Article 12 of the Universal Declaration of Human Rights and Article 17 of the International Covenant on Civil and Political Rights (ICCPR)

Politicians often frame these bans as measures against extremism, equating masked protesters with hate groups like the Ku Klux Klan. However, this comparison ignores the historical context: the KKK’s masks were used to conceal criminal activity and intimidation, while modern activists use masks for safety and anonymity.

Such bans are not about public safety but about maintaining power. They disproportionately target movements advocating for racial justice, environmental protection, and Palestinian rights, while white supremacist groups often face little to no enforcement. This selective application reveals the underlying bias in these policies.

5. Expansion of Powers

These laws empower police and property owners to demand mask removal, which has and will lead to abuse of power and selective enforcement that disproportionately impacts marginalized communities and inhibit First Amendment rights. 
Mask bans discourage individuals with health conditions or disabilities from protecting themselves and repersent an authoritarian attempt to suppress dissent and enforce conformity.

6. Legal and Ethical Implications

The legal implications of mask bans are troubling. Beyond the ADA and the First Amendment, these bans may violate international human rights standards. The Universal Declaration of Human Rights guarantees the right to health and the freedom of expression (United Nations). Mask bans infringe on both by preventing individuals from protecting themselves and expressing their beliefs.

Ethically, these policies fail the test of equity. Public health measures should prioritize the most vulnerable, not marginalize them further. Mask bans signal a disregard for collective responsibility, replacing compassion with coercion.

7. Conclusion

This fight isn’t just for disabled people—it’s for everyone who values freedom. Disabilities can affect anyone at any time, and protecting the rights of the vulnerable is essential. Lawsuits challenging mask bans may increase, as they should. We must recognize that these bans infringe on rights and perpetuate harmful discrimination.

The hypocrisy is blatant. Many who railed against mask mandates during the pandemic now back mask bans, exposing their real motive: controlling others, not protecting freedom. It’s the same playbook used to enforce oppressive religious and societal norms while claiming to champion liberty. These bans aren’t about safety or justice—they’re about silencing dissent and maintaining power for a select few.

Much of the information in this section I a summary of this video, please check it out to support that channel and learn more: [Some More News - Mask Bans](https://youtu.be/XTNBMVoFqN8?si=kvrvwtuGsiLRsKs5)

8. What can we do?

Support Litigation: Donate to organizations challenging mask bans in court, such as the ACLU or Disability Rights Advocates.

Raise Awareness: Share stories of individuals impacted by mask bans to highlight their real-world consequences.

Advocate for Change: Contact legislators to demand policies that respect public health and constitutional rights.

Contribute to or help support this project in whatever way you can.

Respirators like the 3M 6000 series offer better face comfort compared to disposable dust masks and keep hot air off the face, and I aim to build on that technology for broader and more creative daily use.

I believe in promoting the normalization of mask-wearing in society, not just for protection but as a form of self-expression. With growing concerns about pollution, microplastics, and airborne diseases, wearable filters will become more important for our collective future. By developing open, modular, and functional headgear, I hope to support a creative outlet for the community and help others embrace volentary personal protection in more contexts.

An extremely important note to make is that for many people mask wearing and protecting one's body are extremely important religious and cultural rights that should not be disrespected, appropreated, or the expression of suppressed.

Here is a list of a few:

Christianity:
1 Corinthians 6:19-20: “Your body is a temple of the Holy Spirit... therefore honor God with your bodies.”

Exodus 34:29-35 (The Bible): Moses veils his face after descending from Mount Sinai because his face shines from speaking with God. Many modern Christians speak with God regurally, and are often called to action by God. They would be following Moses' tradition by covering their face.

During the COVID-19 pandemic, many churches referenced Leviticus 13:45-46, which outlines isolation and covering the mouth of individuals with contagious conditions, as biblical support for mask-wearing.

Judaism:

Isaiah 6:2: Describes seraphim covering their faces in the presence of God, which can symbolize reverence and humility.

Masks and costumes are central to Purim celebrations, expressing joy and creativity in a religious context.

Buddhism:

Dhammapada 231-233: “One should guard oneself... Protect your body, for it is the vehicle of your spirit.” This emphasizes taking care of one’s body, which can extend to wearing masks for health or ritual purposes.
    
Buddhist monks and practitioners in some traditions wear face coverings (e.g., in Japan and Korea) to protect life, reflecting the principle of Ahimsa (non-harm).

Sikhism:

Guru Granth Sahib: “Body and mind belong to the One who owns the soul... Preserve the self in purity.” (SGGS, Ang 727). Sikh teachings emphasize maintaining health and cleanliness as part of spiritual discipline.

Taoism:

Tao Te Ching 50: “He who protects his body as sacred has found his purpose.”

Hindu:

In Hindu traditions, masks are often used in performances like Kathakali or Ramayana reenactments, symbolizing deities and characters.

Shinto:

Masks are worn in traditional rituals to represent kami (spirits) and protect participants in sacred spaces from impurity.

Indigenous Spiritualities:

Masks play a significant role in Native American, Australian Aboriginal, African, and other indigenous ceremonies. They are worn for expression, storytelling, and connecting with the spiritual world. Many of these traditions have been lost but if anyone would like to share specific examples please reach out to me.

This is not an exaustive list and I am not an expert, but there is enough information here to show that determining if an individual's reasion for wearing a mask is either religion or medical is an impossible task without verbally enguaging with them, which authorities often will not have proper legal cause to do. This information is here to help protect the public and give aid to those who wish to challenge unjust or unconstitutional laws in the United States. I make no warrenties, do your own research. I am not a lawyer, I am a silly clown person who says silly clown things.

