# Happy Paws — Animal Shelter Website

A multi-page website for a pet adoption shelter, built with HTML and CSS.

**Live site:** https://happy-paws-shelter-website.netlify.app/   /  
https://biancasud.github.io/Project-8-Happy-Paws/

![Happy Paws]
<img width="1844" height="940" alt="image" src="https://github.com/user-attachments/assets/c21de1a5-593c-4371-90da-9cbb9ae365e6" />
<img width="401" height="826" alt="image" src="https://github.com/user-attachments/assets/8585552a-b89d-4821-bc41-f2851f141f04" />



## About

Happy Paws presents adoptable animals, explains how the adoption process works, and lets visitors submit a pet for rehoming. It is the largest project in my portfolio in terms of page count and form complexity.

## Features

- **Adoption catalogue** — pet cards showing name and age, with entry points for dogs, cats, other animals and shelter search
- **Adoption process section** breaking the journey into three clear steps
- **Blog area** split into cat articles and dog articles, covering care guides, naming and behavior 
- **Pet surrender form** with:
  - a dropdown listing 20 animal types
  - radio buttons for gender and for age unit (months / years)
  - a file input for uploading a photo
  - required-field markers and contact fields
- **Multiple shelter locations** with addresses and phone numbers
- **Structured footer** organized into resources, cats, dogs and other animals

## Built with

HTML5, CSS3. No frameworks or libraries.

## Running locally

```bash
git clone https://github.com/BiancaSud/Project-8-Happy-Paws.git
cd Project-8-Happy-Paws
```

Open `index.html` in a browser.

## What I focused on

The form was the main challenge. It uses almost every input type — text, select, radio, file, email, tel — and required thinking about grouping and labelling so that a long form does not feel overwhelming. Laying out the pet catalogue as a repeating card component also taught me to design one block properly and reuse it, rather than styling each entry individually.

## Possible improvements

- Client-side form validation and a submission confirmation state (currently the form is presentation only)
- Responsive breakpoints for tablet and mobile
- Filtering the pet catalogue by type and age
