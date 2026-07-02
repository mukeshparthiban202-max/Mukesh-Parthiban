<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mukesh Parthiban - Resume</title>
    <style>
        :root {
            --primary-color: #1e3a8a; /* Deep Navy Blue */
            --secondary-color: #0f172a; /* Slate Dark */
            --text-color: #334155; /* Neutral Dark for body text */
            --light-bg: #f8fafc; /* Soft gray for backgrounds */
            --accent-color: #2563eb; /* Vibrant Blue for links/accents */
            --border-color: #e2e8f0;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: #f1f5f9;
            padding: 40px 20px;
        }

        .resume-container {
            max-width: 950px;
            margin: 0 auto;
            background: #fff;
            padding: 50px;
            border-radius: 8px;
            box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
        }

        /* Header Style */
        header {
            border-bottom: 3px solid var(--primary-color);
            padding-bottom: 25px;
            margin-bottom: 30px;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            flex-wrap: wrap;
            gap: 20px;
        }

        .header-left h1 {
            font-size: 2.5rem;
            color: var(--secondary-color);
            font-weight: 700;
            letter-spacing: -0.5px;
        }

        .header-left h2 {
            font-size: 1.25rem;
            color: var(--accent-color);
            font-weight: 600;
            margin-top: 5px;
        }

        .header-right {
            text-align: right;
            font-size: 0.95rem;
        }

        .header-right a {
            color: var(--accent-color);
            text-decoration: none;
        }

        .header-right a:hover {
            text-decoration: underline;
        }

        /* Layout Grid */
        .main-layout {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 40px;
        }

        @media (max-width: 768px) {
            .main-layout {
                grid-template-columns: 1fr;
            }
            header {
                flex-direction: column;
            }
            .header-right {
                text-align: left;
            }
            body {
                padding: 15px 10px;
            }
            .resume-container {
                padding: 20px;
            }
        }

        /* Section Universals */
        section {
            margin-bottom: 35px;
        }

        h3.section-title {
            font-size: 1.3rem;
            color: var(--primary-color);
            text-transform: uppercase;
            letter-spacing: 1px;
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 6px;
            margin-bottom: 15px;
        }

        /* Left Column Styles */
        .profile-text, .objective-text {
            font-size: 1rem;
            margin-bottom: 15px;
            text-align: justify;
        }

        .job-card {
            margin-bottom: 25px;
        }

        .job-header {
            display: flex;
            justify-content: space-between;
            font-weight: 600;
            color: var(--secondary-color);
            margin-bottom: 5px;
        }

        .job-company {
            color: var(--accent-color);
            font-style: italic;
            margin-bottom: 8px;
            font-size: 0.95rem;
        }

        .job-bullets {
            list-style-type: square;
            margin-left: 20px;
            font-size: 0.95rem;
        }

        .job-bullets li {
            margin-bottom: 6px;
        }

        /* Right Column Styles */
        .right-col .section-content {
            background-color: var(--light-bg);
            padding: 20px;
            border-radius: 6px;
            margin-bottom: 25px;
        }

        .tech-category {
            margin-bottom: 15px;
        }

        .tech-category strong {
            display: block;
            color: var(--secondary-color);
            font-size: 0.95rem;
            margin-bottom: 4px;
        }

        .tech-category p {
            font-size: 0.9rem;
        }

        .info-list, .education-list, .achievement-list {
            list-style: none;
        }

        .info-list li, .education-list li, .achievement-list li {
            font-size: 0.9rem;
            margin-bottom: 10px;
        }

        .education-list li strong {
            color: var(--secondary-color);
            display: block;
        }

        .achievement-list li {
            position: relative;
            padding-left: 20px;
        }

        .achievement-list li::before {
            content: "🏆";
            position: absolute;
            left: 0;
            top: 0;
        }

        /* Footer declaration */
        footer {
            margin-top: 20px;
            border-top: 1px solid var(--border-color);
            padding-top: 15px;
            font-size: 0.85rem;
            font-style: italic;
            text-align: center;
        }
    </style>
</head>
<body>

<div class="resume-container">
    
    <header>
        <div class="header-left">
            <h1>Mukesh Parthiban</h1>
            <h2>Senior Accountant & Automation Specialist</h2>
        </div>
        <div class="header-right">
            <p>📍 Chennai, India</p>
            <p>📞 +91 90800 32647</p>
            <p>✉️ <a href="mailto:mukeshparthiban202@gmail.com">mukeshparthiban202@gmail.com</a></p>
            <p>🔗 <a href="https://www.linkedin.com/in/mukesh-parthiban" target="_blank">linkedin.com/in/mukesh-parthiban</a></p>
        </div>
    </header>

    <div class="main-layout">
        
        <!-- LEFT COLUMN: Main Experience & Profiles -->
        <div class="left-col">
            
            <section id="profile">
                <h3 class="section-title">Personal Profile</h3>
                <p class="profile-text">
                    Senior Accountant with 6 years of R2R and taxation experience at global firms. Expert in SAP/Oracle workflows, specialized in building Python and AI automation pipelines to optimize month-end closes.
                </p>
            </section>

            <section id="objective">
                <h3 class="section-title">Objective</h3>
                <p class="objective-text">
                    Seeking a challenging opportunity in an organization to excel and grow along with the organization by utilizing my knowledge and acquired skills towards fulfillment of organizational vision.
                </p>
            </section>

            <section id="experience">
                <h3 class="section-title">Professional Experience</h3>
                
                <!-- Job 1 -->
                <div class="job-card">
                    <div class="job-header">
                        <span>Senior Specialist</span>
                        <span>Jan 2025 - Present</span>
                    </div>
                    <div class="job-company">BNY Mellon Operations India Pvt Ltd.</div>
                    <ul class="job-bullets">
                        <li><strong>Financial Operations:</strong> Manage end-to-end R2R processes, including VAT settlements, cap fees, audit/expense accruals, prepaids, GAAP adjustments, Riester underfunding and executive reporting activities.</li>
                        <li><strong>Reporting & Analysis:</strong> Orchestrate monthly asset register preparation, Advantage & Firee reconciliations, MPA checks, and AP Ageing Report, VAT Continental, and Error & Loss reports.</li>
                        <li><strong>Month-End Close:</strong> Conduct deep-dive P&L analysis and post ad-hoc journals to ensure seamless, timely monthly closes in close coordination with global onshore teams.</li>
                        <li><strong>AI & Python Automation:</strong> 
                            <ul>
                                <li>Designed and implemented an automated VAT settlement workflow utilizing Excel Power Query (M Code) and Office Scripts to replace manual data assembly.</li>
                                <li>Engineered an automated reporting solution for AP Ageing using HTML, CSS, JavaScript, and advanced AI integration.</li>
                                <li>Built robust automated report extraction pipelines using Python, Selenium, and Playwright with AI assistance.</li>
                                <li>Deployed batch script-based automation to streamline daily file transfer operations.</li>
                            </ul>
                        </li>
                    </ul>
                </div>

                <!-- Job 2 -->
                <div class="job-card">
                    <div class="job-header">
                        <span>Senior Account Executive</span>
                        <span>Aug 2022 - Dec 2024</span>
                    </div>
                    <div class="job-company">CMA CGM Shared Service Centre</div>
                    <ul class="job-bullets">
                        <li><strong>Asset Management & BRS:</strong> Oversaw capitalization of fixed assets, asset creation, and acquisition within SAP. Uploaded bank statements across SAP and Oracle, managing targeted clearing of bank accounts alongside AP/AR teams.</li>
                        <li><strong>Journal Ledger Operations:</strong> Prepared and posted critical adjustments, including depreciation journals, salary journals, tax entries, course differences, and AP/AR cash splits.</li>
                        <li><strong>Reconciliations & Close:</strong> Managed comprehensive balance sheet reconciliations for Debtors, Creditors, Accruals, and Tax accounts. Executed monthly revaluation entries and final OneStream data submissions.</li>
                        <li><strong>Process Engineering:</strong> Implemented customized Excel Macros for daily volume trackers and data load preparation into Oracle. Spearheaded project activities for AP Cash Split (Phases 1 & 2) and AR Local to SA workflows.</li>
                    </ul>
                </div>

                <!-- Job 3 -->
                <div class="job-card">
                    <div class="job-header">
                        <span>Account Associate</span>
                        <span>May 2021 - July 2022</span>
                    </div>
                    <div class="job-company">Larsen & Toubro Constructions (L&T)</div>
                    <ul class="job-bullets">
                        <li><strong>Reconciliation & Tracking:</strong> Performed daily bank statement reconciliations in SAP to clear open lines, updating UTR numbers across SAP and Onex systems for flawless payment tracking.</li>
                        <li><strong>Taxation & Amortization:</strong> Posted compliant journal entries for TDS, PF payments, and GST in SAP, while performing monthly amortization for precise financial reporting.</li>
                        <li><strong>Auditing Support:</strong> Managed reconciliations for TDS, GST, PF, advance accounts, and fixed asset registers. Handled query resolution with system initiators.</li>
                    </ul>
                </div>

                <!-- Job 4 -->
                <div class="job-card">
                    <div class="job-header">
                        <span>Junior Accountant</span>
                        <span>Sep 2020 - May 2021</span>
                    </div>
                    <div class="job-company">Enterprising Enterprises Granite Industries</div>
                    <ul class="job-bullets">
                        <li><strong>Core Bookkeeping:</strong> Maintained comprehensive financial ledgers, vouchers, and records in Tally ERP-9, managing cash, bank, purchase, and sales entries.</li>
                        <li><strong>Tax Filings & Collections:</strong> Input invoice details directly into GSTR-1, processed tax/TDS entries, and established consistent follow-ups with customers to optimize accounts receivable collections.</li>
                    </ul>
                </div>

            </section>
        </div>

        <!-- RIGHT COLUMN: Sidebar (Skills, Education, Personal Details) -->
        <div class="right-col">
            
            <section id="skills">
                <h3 class="section-title">Core Competencies</h3>
                <div class="section-content">
                    <div class="tech-category">
                        <strong>Financial Expertise:</strong>
                        <p>Record-to-Report (R2R), General Ledger (GL) Accounting, P&L Analysis, BRS, Fixed Asset Management, Accruals & Prepaids.</p>
                    </div>
                    <div class="tech-category">
                        <strong>ERP Systems:</strong>
                        <p>SAP (T-codes: FB03, FBLIN, FBL5N, FBL3N, F-03, FBV0, FEBAN, FBRA), Oracle (AP, AR, GL Modules), Tally ERP-9.</p>
                    </div>
                    <div class="tech-category">
                        <strong>Automation & Tech:</strong>
                        <p>Python (Selenium, Playwright), Excel Power Query (M Code), Office Scripts (Macros), HTML, CSS, JavaScript, Batch Scripting.</p>
                    </div>
                </div>
            </section>

            <section id="education">
                <h3 class="section-title">Education</h3>
                <div class="section-content">
                    <ul class="education-list">
                        <li>
                            <strong>MBA (General) - 2023</strong>
                            Loyola College (PULC) | Score: 62.1%
                        </li>
                        <hr style="margin: 10px 0; border: 0; border-top: 1px solid var(--border-color);">
                        <li>
                            <strong>B.Com (General) - 2020</strong>
                            D.D.G.D. Vaishnav College | Score: 74.8%
                        </li>
                        <hr style="margin: 10px 0; border: 0; border-top: 1px solid var(--border-color);">
                        <li>
                            <strong>HSC (State Board) - 2017</strong>
                            SRM Hr. Sec. School | Score: 96.5%
                        </li>
                        <hr style="margin: 10px 0; border: 0; border-top: 1px solid var(--border-color);">
                        <li>
                            <strong>SSLC (State Board) - 2015</strong>
                            SRM Hr. Sec. School | Score: 97.0%
                        </li>
                    </ul>
                </div>
            </section>

            <section id="achievements">
                <h3 class="section-title">Achievements</h3>
                <div class="section-content">
                    <ul class="achievement-list">
                        <li>Samurai Award (Within 4 months of joining)</li>
                        <li>Mega Star Award</li>
                        <li>Best Performer Award (L&T)</li>
                        <li>VIP Recognition Award (BNY Mellon)</li>
                    </ul>
                </div>
            </section>

            <section id="personal-details">
                <h3 class="section-title">Personal Details</h3>
                <div class="section-content">
                    <ul class="info-list">
                        <li><strong>DOB:</strong> 20/02/2000</li>
                        <li><strong>Gender:</strong> Male</li>
                        <li><strong>Languages:</strong> Tamil & English</li>
                        <li><strong>Address:</strong> No. 533/A, 2 Cross street, Lakshmi Nagar, Aarikambedu, Chennai 600062.</li>
                    </ul>
                </div>
            </section>

        </div>
    </div>

    <footer>
        <p>I hereby declare that the above furnished information are true to the best of my knowledge.</p>
    </footer>

</div>

</body>
</html>
