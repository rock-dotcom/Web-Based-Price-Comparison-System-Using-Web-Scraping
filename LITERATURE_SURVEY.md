# Literature Survey

## Paper 1: E-commerce Price Comparison Website Using Web Scraping

**Source:** IJIRMPS Volume 11, Issue 3 (May-June 2023)  
**DOI:** https://doi.org/10.37082/IJIRMPS.v11.i3.230223  
**File Reference:** paper-1-LS.pdf  

**Objective:**  
Build price comparison website using web scraping to help consumers find best deals across e-commerce platforms, saving time and money.

**Methodology:**  
Web scraping from multiple e-commerce sites (Amazon, Flipkart, Snapdeal, Croma)  
PHP libraries for HTML parsing (Simple HTML DOM Parser)  
Local MySQL database storage of scraped product data  
Web interface built with HTML/CSS/JavaScript for price comparison and alerts  

**Key Features:**  
Real-time price comparison across major e-commerce platforms  
Best deal highlighting with color coding  
Price alerts for favorite products via email notifications  
User-friendly single interface with search functionality  
Historical price tracking charts  

**Limitations:**  
Dependent on e-commerce site structure changes requiring code updates  
PHP-based scraping may face rate limiting and IP blocking  
Limited to predefined e-commerce sites (4 platforms only)  
No mobile responsiveness in original implementation  

**Relevance to Our Project:**  
HIGH - Direct implementation of price comparison using web scraping from Indian e-commerce sites, provides complete system architecture  

---

## Paper 2: Analysis and Implementation of Web Scrapers

**Source:** Lappeenranta–Lahti University of Technology LUT Bachelor's Thesis 2025  
**DOI:** N/A (University Thesis)  
**File Reference:** paper4-LS.pdf  

**Objective:**  
Analyze web scraping techniques through literature review and implement practical scraper for product price/review comparison using EAN codes across Finnish retailers.

**Methodology:**  
Comprehensive literature review comparing scraping libraries (BeautifulSoup, Selenium, Playwright)  
Playwright library implementation for dynamic JavaScript content handling  
EAN code-based product matching across multiple retailer websites  
Frontend HTML/JavaScript interface with Python Flask backend server  
CSV file export of collected product data (price, reviews, availability)  

**Key Features:**  
Multi-site scraping capability (Gigantti, Verkkokauppa, Power, Prisma)  
Handles dynamic JavaScript content and anti-bot measures  
Legal/ethical considerations including robots.txt compliance and rate limiting  
Product comparison using standardized EAN codes  
Simple web interface for EAN code input and results display  

**Limitations:**  
Limited to pre-registered stores only (not scalable to new sites)  
Requires EAN codes (users must know product codes)  
Site structure changes break scraper functionality  
Finnish retailers only, not applicable to Indian market  
No persistent database storage  

**Relevance to Our Project:**  
VERY HIGH - Complete working scraper implementation with detailed methodology, Playwright usage guidance, and ethical considerations  

---

## Paper 3: An Efficient Mechanism for Product Data Extraction from E-Commerce Websites

**Source:** Computers, Materials & Continua (CMC), vol.65, no.3, pp.2639-2663, 2020  
**DOI:** 10.32604/cmc.2020.011485  
**File Reference:** paper-8-LS.pdf  

**Objective:**  
Develop automatic, unsupervised technique to extract structured product data records from semi-structured e-commerce web pages using visual and structural analysis.

**Methodology:**  
Rich Data Region (RDR) detection using user query keywords and correlative terms  
Style similarity clustering to segment RDR into individual data records  
Formatting entropy calculation to differentiate data records from menus/ads  
Common Tag Sequence (CTS) identification for noise removal  
Java implementation using JSOUP HTML parser on real-world e-commerce sites  

**Key Features:**  
Achieves 99.2% precision and 98.4% recall on real e-commerce datasets  
Handles noisy elements (menus, advertisements, pagination links) automatically  
No training data or manual annotation required (fully unsupervised)  
Works across diverse e-commerce page templates and structures  
Visual cues and DOM tree analysis for robust extraction  

**Limitations:**  
Assumes symmetric formatting of data records across page  
Java-based implementation (not Python as preferred)  
Tested primarily on specific datasets, generalizability uncertain  
Computationally intensive for very large pages  

**Relevance to Our Project:**  
CRITICAL - Provides theoretical foundation for identifying and extracting product data regions from complex e-commerce pages  

---

## Paper 4: Web Scraping Based Site for Product Analysis

**Source:** International Journal for Multidisciplinary Research (IJFMR) Volume 6, Issue 3, May-June 2024  
**DOI:** IJFMR240320817  
**File Reference:** LS-p4.pdf  

**Objective:**  
Create comprehensive web scraping platform for competitive analysis, price comparison, and market insights from multiple e-commerce platforms.

**Methodology:**  
Strategic target e-commerce platform selection based on market share  
Development of robust, modular scraping modules for each platform  
Structured data collection pipeline (price, description, reviews, stock status, ratings)  
Multi-stage data cleaning and validation processes  
MongoDB storage with analytics dashboard using Chart.js visualization  

**Key Features:**  
Multi-platform price comparison and historical trend analysis  
Automated review sentiment analysis and rating aggregation  
Competitor price monitoring with anomaly detection  
Market trend identification and demand forecasting capabilities  
Interactive analytics dashboard with real-time visualizations  

**Limitations:**  
Requires continuous legal/ethical scraping compliance monitoring  
Scalability challenges for enterprise-level operations  
Complex handling of dynamic content and anti-bot measures  
High initial development and maintenance costs  

**Relevance to Our Project:**  
HIGH - Provides analytics-focused scraping system architecture and market intelligence approach  

---

## Paper 5: Price Comparison Application for E-Commerce Using Web Scraping

**Source:** IARJSET Conference Proceedings 2025  
**DOI:** IARJSET.2025.12431  
**File Reference:** LS-p1.pdf  

**Objective:**  
Develop real-time price comparison tool across major Indian e-commerce platforms with advanced product matching and user analytics.

**Methodology:**  
Python Flask backend with Streamlit frontend interface  
Multi-site scrapers for Amazon.in, Flipkart, Myntra, Meesho, Croma, Nykaa  
Advanced product matching engine using UPC/EAN/Model# and similarity analysis  
SQLite database for persistence with statistical analysis capabilities  
Randomized HTTP headers and session management for anti-detection  

**Key Features:**  
Comprehensive product matching across 8+ Indian e-commerce platforms  
Wishlist tracking with price drop notifications  
Statistical insights including price distribution and platform reliability scores  
User authentication with personalized price history  
Responsive web interface with sorting/filtering options  

**Limitations:**  
Frequent website structure changes require scraper maintenance  
Complex product variation matching (different colors/sizes)  
Regional pricing differences and dynamic discounts challenging  
Rate limiting and CAPTCHAs on high-traffic sites  

**Relevance to Our Project:**  
VERY HIGH - Complete Python implementation targeting Indian market with advanced matching algorithms  

---

## Paper 6: Web Scraping based Product Comparison Model for E-Commerce

**Source:** JETIR Volume 9, Issue 4, April 2024  
**DOI:** JETIR2404G32  
**File Reference:** LS-p2.pdf  

**Objective:**  
Build automated product comparison dashboard with real-time price tracking and threshold-based alert system.

**Methodology:**  
.NET Core backend with MySQL database  
Selenium WebDriver with Chrome browser automation  
Cloud-hosted scraping service with scheduled updates  
Threshold-based notification system via email/SMS  
Responsive dashboard using ASP.NET MVC and Bootstrap  

**Key Features:**  
Real-time interactive dashboard with live price updates  
Configurable price drop alerts with multiple notification channels  
Multi-platform comparison with visual indicators  
Historical price tracking with trend charts  
Cloud deployment ready for scalability  

**Limitations:**  
.NET technology dependency (not Python ecosystem)  
Cloud hosting incurs operational costs  
Limited to predefined price thresholds  
Selenium overhead increases resource consumption  

**Relevance to Our Project:**  
HIGH - Excellent dashboard and alert system implementation, cloud deployment guidance  

---

## Paper 7: Online Shopping Item Cost Analysis through Web Scraping

**Source:** IJISRT Volume 9, Issue 6, June 2024  
**DOI:** IJISRT24JUN1016  
**File Reference:** LS-p3.pdf  

**Objective:**  
Create Node.js based price comparison engine with comprehensive user interface and multi-site coverage.

**Methodology:**  
Node.js with Puppeteer for headless browser scraping  
Express.js REST API backend architecture  
MongoDB for NoSQL data storage  
Advanced data processing pipeline with normalization  
React frontend with Material-UI components  

**Key Features:**  
Modern Node.js stack with excellent performance  
User-friendly search interface with autocomplete  
Comprehensive price analysis across multiple categories  
Real-time data processing and caching  
Progressive Web App (PWA) capabilities  

**Limitations:**  
Node.js single-threaded nature limits concurrent scraping  
JavaScript-heavy sites challenging for Puppeteer  
Higher memory consumption compared to Python solutions  
Steeper learning curve for .NET/Python developers  

**Relevance to Our Project:**  
MEDIUM - Alternative Node.js methodology and modern UI patterns  

---

## Paper 8: Automated Web Scraping and Data Visualization from Multiple E-commerce Websites

**Source:** SRM Valliammai Engineering College Technical Symposium 2025  
**DOI:** N/A (Conference Proceedings)  
**File Reference:** LS-P5.pdf  

**Objective:**  
Implement automated scheduled scraping with interactive data visualization for price trend analysis.

**Methodology:**  
Python Scrapy framework for distributed scraping  
PostgreSQL database with scheduled scraping jobs (Celery)  
Plotly Dash for interactive visualization dashboard  
Redis caching for performance optimization  
Docker containerization for deployment  

**Key Features:**  
Automated scheduled scraping with cron-like functionality  
Interactive price trend charts and comparison visualizations  
Historical data analysis spanning months  
Responsive dashboard with drill-down capabilities  
Production-ready Docker deployment  

**Limitations:**  
Complex Plotly visualization overhead  
Large historical data storage requirements  
Scrapy learning curve for beginners  
Resource-intensive for real-time updates  

**Relevance to Our Project:**  
HIGH - Complete visualization solution and production deployment patterns  

---

## Paper 9: E-commerce Price Monitoring and Comparison System

**Source:** IRJMETS Volume 5, Issue 5, May 2024  
**DOI:** IRJMETS1714997074  
**File Reference:** paper-2-LS.pdf  

**Objective:**  
Develop competitor price monitoring system with AI-powered scraping and automated business intelligence.

**Methodology:**  
Python with Firecrawl AI scraping service integration  
Streamlit dashboard with real-time updates  
6-hour automated update cycles with anomaly detection  
Pinecone vector database for product matching  
Business intelligence metrics and competitor analysis  

**Key Features:**  
AI-powered scraping bypasses traditional anti-bot measures  
Advanced competitor tracking with price difference metrics  
One-click access to lowest price across platforms  
Automated business reports and insights  
Modern Streamlit interface with excellent UX  

**Limitations:**  
Dependency on third-party AI scraping service (costly)  
6-hour update frequency (not real-time)  
Complex dashboard may overwhelm casual users  
Vendor lock-in with Firecrawl service  

**Relevance to Our Project:**  
VERY HIGH - Modern AI scraping techniques and business intelligence approach  

---

# Literature Survey Table

| Paper Title | Authors | Year | Key Focus | Applications | Challenges |
|------------|---------|------|-----------|-------------|------------|
Analysis and Implementation of Web Scrapers | Tom Malinen | 2025 | Playwright scraper with literature analysis | EAN-based multi-retailer price/review comparison | EAN code dependency; Finnish sites only; no database paper4-LS.pdf  
Price Comparison Application for E-Commerce | IARJSET Conference authors | 2025 | Advanced Python matching algorithms | 8+ Indian platforms (Amazon.in, Flipkart, Myntra) | Product variation matching; CAPTCHA handling LS-p1.pdf  
Automated Web Scraping and Data Visualization | SRM Valliammai authors | 2025 | Scrapy+Plotly production deployment | Scheduled scraping with interactive trend charts | High resource usage; Scrapy learning curve LS-P5.pdf  
E-commerce Price Monitoring System | IRJMETS authors | 2024 | AI-powered Firecrawl competitor tracking | Business intelligence dashboards, anomaly detection | Third-party service costs; 6-hour update cycles paper-2-LS.pdf  
Online Shopping Item Cost Analysis | IJISRT authors | 2024 | Node.js Puppeteer with React UI | PWA-enabled modern interface, real-time caching | Single-threaded scraping; memory intensive LS-p3.pdf  
Web Scraping Product Comparison Model | JETIR authors | 2024 | .NET dashboard with threshold alerts | Cloud-hosted real-time price tracking | .NET ecosystem lock-in; Selenium overhead LS-p2.pdf  
Web Scraping Based Site for Product Analysis | Not specified | 2024 | Competitive intelligence platform | Multi-platform trend analysis, sentiment analysis | Legal compliance monitoring; anti-bot measures LS-p4.pdf  
E-commerce Price Comparison Website | Shaikh et al. | 2023 | PHP-based complete system implementation | Amazon/Flipkart alerts, historical charts | PHP rate limiting; site structure fragility paper-1-LS.pdf  
Product Data Extraction Mechanism | Malik Javed Akhtar et al. | 2020 | RDR+CTS unsupervised extraction | Noisy e-commerce page product extraction | Symmetric formatting assumption; Java-based paper-8-LS.pdf  
