# Child Diarrhoea Triage Guide

A simple web page that helps a parent or caregiver decide what to do when a child under 5 has diarrhoea: go to emergency care, visit a clinic soon, or care for the child at home.

This is a **learning project** built for the Health and Humanity track idea of the IEEE Day Buildathon. It is not a medical device.

## The problem and who it is for

Diarrhoea can cause dangerous dehydration in young children. Many parents cannot easily tell a mild case from a serious one, and clinics can be far away. This guide is for parents and caregivers of children under 5.

## What it does

The guide asks up to 11 simple yes/no questions, one at a time, and then shows one of three results:

- **Emergency:** take the child to a health facility now
- **Clinic soon:** visit a health facility today
- **Home care:** give ORS, keep feeding, and watch for danger signs

If any danger sign is present, it gives the emergency result immediately.

## What it does not do

- It does not diagnose.
- It does not replace a health worker.
- It gives no medicine doses.
- It stores or sends no personal data.

## Where the guidance comes from

The questions are based on WHO guidance for classifying dehydration in children (Integrated Management of Childhood Illness, IMCI). The danger-sign rule is deliberately more cautious than WHO's, because a parent cannot reliably judge every sign.

Clinical review: Not yet reviewed by a health professional. Not for real-world use.

## Tech stack

Plain HTML, CSS and JavaScript in a single file (`index.html`). No libraries, no backend, no database.

## How to run it

1. Download `index.html`.
2. Double-click it to open it in a web browser.

Live demo: Coming soon

## AI usage

- Google AI Studio was used to generate the first version of the code.
- Claude (by Anthropic) was used to plan the project, draft the question flow, review the code, and fix a safety-ordering issue.
- I tested the guide myself and I am learning to explain how every part of the code works.

## Who did what

Built by Nicole Chebet as a solo learning project.

## Limitations and next steps

- Questions are in English only. A Swahili version is planned.
- It covers children under 5 only.
- Terms like ORS are not yet explained on screen.
- There is no Back button yet.
- The question flow needs review by a health professional before any real-world use.
