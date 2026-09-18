# flowfix\_plumbing
My plumbing website
WEDE5020 Portfolio of Evidence (PoE) - Part 2 
FlowFix Plumbing Services Website 
Student Information 
 
 
 
 
 --- 
Student Name: Nkateko Sehlahla 
Student ID: ST10512172 
Module Code: WEDE5020 (Web Development Introduction) 
Assessment Phase: Formative 2 (Part 2 - CSS Styling and Responsive Design) 
Date: September 2026 
Project Overview 
FlowFix Plumbing Services is a professional small business website developed as part of the WEDE5020 
Portfolio of Evidence. 
 
Part 1 Focus: Website Initiation, Proposals, Directory File Structure, and Semantic HTML5 
Foundation. 
 
Part 2 Focus: Visual Styling using a single External Stylesheet (`css/style.css`), CSS Box Model 
Layouts, Typography, Decoration, Interactive Pseudo-Classes, and Responsive Web Design via Media 
Queries. --- 
Implementation Details for Part 2 
1. Implementation of Feedback from Part 1 
 
File & Directory Structure: Organized the root folder strictly using lowercase naming 
conventions with zero special characters or numeric prefixes (`css/`, `images/`, `js/`). 
 
Root HTML Files: Verified that all 5 required pages (`index.html`, `about.html`, `services.html`, 
`enquiry.html`, `contact.html`) sit directly in the root directory. 
 
GitHub Tracking: Recorded step-by-step progress with clear, descriptive commit messages. 
2. External Stylesheet & Base Styles (LU4) 
 
Created a central external CSS stylesheet at `css/style.css` and linked it in the `<head>` of all 5 
HTML files using `<link rel="stylesheet" href="css/style.css">`. 
 
Established a standard CSS Reset using `box-sizing: border-box` to ensure consistent box model 
measurements across browsers. 
 
Set global typography rules using clean system font stacks (`Segoe UI`, `Tahoma`, `sans-serif`) 
with structured heading sizes (`rem` units) and line heights. 
3. Layout, Decoration & Interactive Controls 
 
Flexbox & Box Model: Structured the navigation header, feature cards, and branch location 
cards using Flexbox (`display: flex; gap: 1.5rem;`). 
 
Color Palette & Decoration: Applied a professional color palette—Primary Navy (`#1b4965`), 
Secondary Light Blue (`#62b6cb`), Accent Red (`#e63946`), and Slate Neutral backgrounds (`#f8fafc`). 
 
Interactive Pseudo-Classes: Styled link state transitions (`:link`, `:visited`, `:hover`, `:focus`, 
`:active`) for navigation tabs, call-to-action buttons, and form inputs. 
 
Data Tables & Forms: Styled tables with alternating row colors (`nth-child(even)`), collapsed 
borders, and responsive form field focus states (`box-shadow` and `border-color`). 
4. Responsive Web Design & Media Queries (LU5) 
 
Relative Units: Used relative percentage widths (`%`), `rem`, and `em` to allow text and 
container elements to scale naturally. 
 
 
Fluid Media: Set images to scale fluidly across viewports (`max-width: 100%; height: auto;`). 
Breakpoints: Added `@media screen and (max-width: 960px)` for tablets and `@media screen 
and (max-width: 680px)` for mobile devices to stack horizontal navigation items vertically and collapse 
multi-column flex boxes. --- 
Sitemap 
1. 
2. 
3. 
4. 
5. --- 
`index.html` — Homepage with Hero Banner, Feature Cards, and Operating Hours Table. 
`about.html` — About Us page with Company Mission, Team Photo, and Certification Stats. 
`services.html` — Services & Pricing page with Detailed Rates Table. 
`enquiry.html` — Interactive Quote Request Form with Fieldsets and Inputs. 
`contact.html` — Contact & Depot Locations with Embedded Interactive Google Map. 
References (IIE Harvard Style) 
 
 
Duckett, J. 2011. HTML and CSS: Design and Build Websites. Indianapolis: John Wiley & Sons. 
Mozilla Developer Network (MDN). 2026. CSS: Cascading Style Sheets. Available at: 
https://developer.mozilla.org/en-US/docs/Web/CSS [Accessed 18 September 2026]. 
 
The Independent Institute of Education (IIE). 2026. Web Development (Introduction) [WEDE5020 
Module Manual]. Johannesburg: IIE. 
 
W3Schools. 2026. CSS Responsive Web Design. Available at: 
https://www.w3schools.com/css/css_rwd_intro.asp [Accessed 18 September 2026]. 
--- 
Detailed Changelog 
 
Commit 1 (Part 1 Correction): Cleaned up root folder structure; removed leading numbers from 
folder names and moved all 5 HTML files to the root directory. 
 
Commit 2 (CSS Setup): Created `css/style.css` with CSS box-model reset (`box-sizing: border
box`), root font stacks, and linked the stylesheet across all 5 HTML pages. 
 
Commit 3 (Layout & Typography): Added Flexbox layout rules for `.header-container`, 
`.features-grid`, and `.contact-grid`. Styled headings (`h1`–`h3`) and paragraph line-heights. 
 
Commit 4 (Decoration & Components): Implemented table styling (`.data-table`), custom form 
inputs, call-to-action buttons (`.btn-primary`), and link state pseudo-classes (`:hover`, `:focus`). 
 
Commit 5 (Responsive Design): Added `@media screen` queries at `960px` and `680px` 
breakpoints to stack mobile navigation menus and collapse multi-column grids. 
 
Commit 6 (Documentation): Updated `README.md` with Part 2 implementation summary, 
references, and changelog records for Part 2 submission.