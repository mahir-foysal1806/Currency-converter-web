## Currency converter
A simple and responsive Currency converter Web application build using Html ,javascript.
It fetches real-time exchange rates from an external API and one currency  to another instantly.
##features 
-Convert between multiple currencies (USD, BDT, EUR, GBP, INR, JPY, CAD, AUD)
-Real-time exchange rate fetching.
-Clean and centered UI design
-Responsive layout
## Technologies Used
-HTML5
-CSS3
-JavaScript (Vanilla JS)
-Exchange Rate API (v6.exchangerate-api.com)
##preview
-The app contains:
-Two dropdowns for selecting currencies
-Input field for base currency
-Auto-calculated converted value
-Live exchange rate display
##How It Works
-User selects base currency.
-App fetches latest exchange rate using fetch() API.
-Selected second currency rate is extracted.
-Converted value is calculated
</>
    Converted Amount = Base Amount × Exchange Rate
    </>

##Installation & Usage
-Clone the repository:
git clone https://github.com/your-username/currency-converter.git
-Open the project folder.
-Open index.html in your browser.
-No additional setup required.

##API Used

Exchange Rate API
Endpoint format:

https://v6.exchangerate-api.com/v6/YOUR_API_KEY/latest/USD

Replace YOUR_API_KEY with your own API key.
##Future Improvements
-Add swap currency button
-Add loading animation
-Add reverse conversion (editable second input)
-Add more currencies
-Dark mode support
-Error message styling
