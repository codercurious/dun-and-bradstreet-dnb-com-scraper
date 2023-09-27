# Dun and Bradstreet Business and Contact Scraper
Interested in using this scraper? Get it here: [Dun and Bradstreet Business and Contact Scraper](https://apify.com/curious_coder/dun-and-bradstreet-dnb-com-scraper)
## How it works

Scrape full company and contacts details data from [Dun and Bradstreet]([https://dnb.com])
Filter your company search by keywords, country, enity type, employee count
Filter your contacts search by keywords and job title

This scraper uses advanced anti-bot algorithms to bypass security challenges and scrape maximum available information. 

## Input options

Take a look at the input options of the scraper in the following screenshot

![Dun and bradstreet scraper options](https://ik.imagekit.io/webscraper/Dun%20and%20bradstreet%20scraper%20options?updatedAt=1695812802150)

## Output

![Dun and bradstreet scraper - Sample company data scraped - 1](https://ik.imagekit.io/webscraper/Dun%20and%20bradstreet%20scraper%20-%20sample%20company%20data%20scraper%20-%201?updatedAt=1695812867159)
![Dun and bradstreet scraper - Sample company data scraped - 2](https://ik.imagekit.io/webscraper/Dun%20and%20bradstreet%20scraper%20-%20sample%20company%20data%20scraped%20-%202?updatedAt=1695812886654)

Here is the sample output of this actor in JSON format:

**Company**
```json
	{
		"companyAddress": "229 W Grand Ave Ste R",
		"companyCity": "Bensenville",
		"companyCountry": "United States",
		"companyProfileLink": "/business-directory/company-profiles.household_finance_corporation.a021ccbe76b65202057dcf5c350b679e.html",
		"companyRegion": "Illinois",
		"companyZipCode": "60106-3365",
		"countryRegion": "Bensenville, IL, United States",
		"duns": "a021ccbe76b65202057dcf5c350b679e",
		"industryName": "Nondepository Credit Intermediation",
		"locationType": "Branch",
		"primaryName": "Household Finance Corporation",
		"tradeStyleNames": "",
		"urlSelector": "household_finance_corporation.a021ccbe76b65202057dcf5c350b679e",
		"industries": {
			"Nondepository Credit Intermediation": "/business-directory/industry-analysis.nondepository_credit_intermediation.html",
			"Credit Intermediation and Related Activities": "/business-directory/industry-analysis.credit_intermediation_and_related_activities.html",
			"Finance and Insurance": "/business-directory/industry-analysis.finance_and_insurance.html",
			"Mortgage bankers and loan correspondents": ""
		},
		"otherIndustries": {
			"Activities Related to Credit Intermediation": "/business-directory/industry-analysis.activities_related_to_credit_intermediation.html",
			"Agencies, Brokerages, and Other Insurance Related Activities": "/business-directory/industry-analysis.agencies_brokerages_and_other_insurance_related_activities.html",
			"Depository Credit Intermediation": "/business-directory/industry-analysis.depository_credit_intermediation.html",
			"Insurance Carriers": "/business-directory/industry-analysis.insurance_carriers.html",
			"Insurance and Employee Benefit Funds": "/business-directory/industry-analysis.insurance_and_employee_benefit_funds.html",
			"Monetary Authorities-Central Bank": "/business-directory/industry-analysis.monetary_authorities-central_bank.html",
			"Other Financial Investment Activities": "/business-directory/industry-analysis.other_financial_investment_activities.html",
			"Other Investment Pools and Funds": "/business-directory/industry-analysis.other_investment_pools_and_funds.html"
		},
		"viewMoreIndustries": {},
		"viewMoreOtherIndustries": {
			"Securities and Commodity Contracts Intermediation and Brokerage": "/business-directory/industry-analysis.securities_and_commodity_contracts_intermediation_and_brokerage.html",
			"Securities and Commodity Exchanges": "/business-directory/industry-analysis.securities_and_commodity_exchanges.html"
		},
		"popularIndustries": [
			{
				"name": "Nondepository Credit Intermediation",
				"url": "/business-directory/company-information.nondepository_credit_intermediation.us.html",
				"colorIndex": 0
			},
			{
				"name": "Credit Intermediation and Related Activities",
				"url": "/business-directory/company-information.credit_intermediation_and_related_activities.us.html",
				"colorIndex": 1
			},
			{
				"name": "Finance and Insurance",
				"url": "/business-directory/company-information.finance_and_insurance.us.html",
				"colorIndex": 2
			}
		],
		"employeesThisSite": {
			"informationScopeDescription": "Individual",
			"reliabilityDescription": "Actual",
			"value": "7",
			"informationScopeDnBCode": 9066,
			"reliabilityDnBCode": 9092,
			"trend": []
		},
		"companyLocation": "229 W Grand Ave Ste R Bensenville, IL, 60106-3365 United States",
		"companyShortSummaryTest": "?",
		"employeesThisSiteReliability": "Actual",
		"employeesThisSiteValue": "?",
		"esgContactUsHrefUrl": "https://service.dnb.com/home",
		"esgIndustryAverage": "?",
		"esgRank": "?",
		"esgRankingHrefUrl": "/about-us/our-analytics/predictors-scores-ratings.html?id=5",
		"keyPrincipal": "Phil Nocita",
		"magentoCartAddDomain": "https://buy.dnb.com",
		"magentoCartAddEndpoint": "/cart/Add/Simplify",
		"magentoCartApiKey": "57b89a4446e66fb0d833d581a34df837",
		"magentoCartDisplayName": "",
		"magentoCartServletPath": "/apps/dnb/thirdparty/AddToCartLinkServlet",
		"magentoCartToken": "Axi1u9YWXq7US5F",
		"magentoCartUniqueId": "tyw2OGxHzug2kKYUIEVvFJGDz8qrRNSr",
		"parentIndustryName": "Finance and Insurance",
		"tradeStyleName": "HFC",
		"website": "www.hsbc.com",
		"encryptedDuns": "a021ccbe76b65202057dcf5c350b679e",
		"isAddressUnverified": true,
		"privateCompany": true,
		"showMoreContactsAnchor": false,
		"showNetGrowthRate": false,
		"showReadMore": false,
		"showRevenueRow": false,
		"showSalesGrowthRate": false,
		"showSeeOtherLocations": true,
		"suppressContactData": false,
		"suppressRevenue": false,
		"sales": 0,
		"isDrs": false,
		"isHu": false,
		"isPl": false
	}
```

**Company fields description**

This documentation provides an explanation of each field present in the JSON data.

1. `companyAddress`: The street address of the company's location.

2. `companyCity`: The city where the company is located.

3. `companyCountry`: The country where the company is located.

4. `companyProfileLink`: A link to the company's profile.

5. `companyRegion`: The region where the company is located.

6. `companyZipCode`: The zip code of the company's location.

7. `countryRegion`: The combined information of the city, state (or region), and country where the company is located.

8. `duns`: The D-U-N-S number of the company, a unique identifier assigned by Dun & Bradstreet.

9. `industryName`: The name of the industry to which the company belongs.

10. `locationType`: The type of location, in this case, it is a branch.

11. `primaryName`: The primary name or title of the company.

12. `tradeStyleNames`: Additional trade style names associated with the company.

13. `urlSelector`: A selector used in constructing URLs related to the company.

14. `industries`: A dictionary that provides information about the industries associated with the company. The keys are industry names, and the values are links to industry analysis.

15. `otherIndustries`: A dictionary providing information about other industries related to the company. The keys are industry names, and the values are links to industry analysis.

16. `viewMoreIndustries`: Additional industries related to the company that can be viewed.

17. `viewMoreOtherIndustries`: Additional industries related to the company that can be viewed, but not categorized under "otherIndustries."

18. `popularIndustries`: A list of popular industries associated with the company. Each entry in the list contains the name, URL, and color index of the industry.

19. `employeesThisSite`: Information about the number of employees at the company's location. It includes the information scope description, reliability description, value, information scope D&B code, reliability D&B code, and trend.

20. `companyLocation`: The complete address of the company including street, city, state (or region), zip code, and country.

21. `companyShortSummaryTest`: A short summary or description of the company (unclear what the actual value is).

22. `employeesThisSiteReliability`: The reliability of the information about the number of employees at the company's location.

23. `employeesThisSiteValue`: The value or number of employees at the company's location (unclear what the actual value is).

24. `esgContactUsHrefUrl`: A URL for contacting the company regarding ESG (Environmental, Social, and Governance) matters.

25. `esgIndustryAverage`: The ESG industry average for the company (unclear what the actual value is).

26. `esgRank`: The ESG rank of the company (unclear what the actual value is).

27. `esgRankingHrefUrl`: A link to information about ESG predictors, scores, and ratings.

28. `keyPrincipal`: The name of the key principal associated with the company.

29. `parentIndustryName`: The name of the parent industry to which the company belongs.

30. `tradeStyleName`: The trade style name associated with the company.

31. `website`: The website URL of the company.

32. `encryptedDuns`: The encrypted version of the D-U-N-S number of the company.

33. `isAddressUnverified`: A boolean indicating whether the company address is verified.

34. `privateCompany`: A boolean indicating whether the company is a private company.

35. `showMoreContactsAnchor`: A boolean indicating whether to show more contact anchors.

36. `showNetGrowthRate`: A boolean indicating whether to show the net growth rate.

37. `showReadMore`: A boolean indicating whether to show a "Read More" option.

38. `showRevenueRow`: A boolean indicating whether to show the revenue row.

39. `showSalesGrowthRate`: A boolean indicating whether to show the sales growth rate.

40. `showSeeOtherLocations`: A boolean indicating whether to show other locations associated with the company.

41. `suppressContactData`: A boolean indicating whether to suppress contact data.

42. `suppressRevenue`: A boolean indicating whether to suppress revenue information.

43. `sales`: The sales value of the company.

44. `isDrs`: A boolean indicating whether the company is related to DRS (Data Reporting Service).

45. `isHu`: A boolean indicating whether the company is related to HU (Human Resources).

46. `isPl`: A boolean indicating whether the company is related to PL (Public Limited).



**Contacts**

Here is the sample json data for a contact:

```json
{
    "givenName": "A",
    "familyName": "Akovenko",
    "title": "Principal",
    "url": "/contact-directory/contact-profile.a_akovenko.744eabd9305633f88a6ebe5c301f3328.html",
    "organizationName": "J & S Marketing",
    "addressRegion": "North Dakota",
    "addressLocality": "Dickinson",
    "addressCountry": "US",
    "contactCompanyProfileHref": "/business-directory/company-profiles.j__s_marketing.5437f9a1c04a5b8a91a96bcfd27fb5d8.html",
    "industryNaicsTwoCodes": "54",
    "industryUrls": [
      {
        "description": "Marketing Consulting Services",
        "url": "/contact-directory/contact-industry-search.management_scientific_and_technical_consulting_services.html"
      }
    ],
    "industryNaicsFourCodes": [
      "5416"
    ],
    "searchCandidates": [
      {
        "displaySequence": 1,
        "contact": {
          "id": "001331092061",
          "givenName": "A",
          "familyName": "Akovenko",
          "organization": {
            "duns": "054126094",
            "primaryName": "J & S Marketing",
            "globalUltimate": {},
            "primaryAddress": {
              "addressCountry": {
                "isoAlpha2Code": "US"
              },
              "addressLocality": {
                "name": "Dickinson"
              },
              "addressRegion": {
                "name": "North Dakota",
                "abbreviatedName": "ND"
              },
              "postalCode": "58601-6726"
            },
            "dunsControlStatus": {
              "operatingStatus": {
                "description": "Active",
                "dnbCode": 9074
              },
              "isMarketable": false,
              "isMailUndeliverable": true,
              "isTelephoneDisconnected": false,
              "isDelisted": false
            },
            "primaryIndustryCodes": [
              {
                "usSicV4": "8742",
                "usSicV4Description": "Management consulting services"
              }
            ],
            "numberOfEmployees": [
              {
                "value": 1,
                "informationScopeDescription": "Consolidated",
                "informationScopeDnBCode": 9067,
                "reliabilityDescription": "Actual",
                "reliabilityDnBCode": 9092
              }
            ],
            "industryCodes": [
              {
                "code": "1055",
                "description": "Advertising & Marketing Services",
                "typeDescription": "D&B Hoovers Industry Code",
                "typeDnbCode": 25838,
                "priority": 1
              },
              {
                "code": "5416",
                "description": "Marketing Consulting Services",
                "typeDescription": "North American Industry Classification System 2022",
                "typeDnbCode": 37788,
                "priority": 1
              }
            ]
          },
          "telephone": [
            {
              "telephoneNumber": "+***********",
              "telephoneAccuracy": {
                "accuracyScore": 90
              }
            }
          ],
          "jobTitles": [
            {
              "title": "Principal"
            }
          ],
          "vanityTitles": [
            {
              "title": "Principal"
            }
          ],
          "managementResponsibilities": [
            {
              "mrcCode": "B1R2"
            }
          ],
          "confidenceLevel": "90",
          "verifiedDate": "2022-06-17"
        }
      }
    ],
    "telephoneNumber": "+***********",
    "organization": {
      "primaryName": "J & S Marketing",
      "telephoneNumber": "(701) 483-5388",
      "streetAddress": "1156 21ST St W APT 723",
      "postalCode": "58601-6726",
      "addressRegion": "North Dakota",
      "addressLocality": "Dickinson",
      "addressCountry": "US",
      "usSicV4Description": "Management consulting services",
      "companyInformationForCookie": {
        "companyAddress": "1156 21ST St W APT 723",
        "companyCity": "Dickinson",
        "companyCountry": "US",
        "companyName": "J & S Marketing",
        "companyState": "North Dakota",
        "companyZip": "58601-6726",
        "encryptedDuns": "5437f9a1c04a5b8a91a96bcfd27fb5d8",
        "completedCreditSignalFlow": false
      }
    }
  }
```

**Contact data fields description**

This documentation provides an explanation of each field present in the JSON data.

1. `givenName`: The given name (first name) of the contact person.

2. `familyName`: The family name (last name) of the contact person.

3. `title`: The title or position of the contact person.

4. `url`: The URL link to the contact person's profile.

5. `organizationName`: The name of the organization associated with the contact person.

6. `addressRegion`: The region or state where the organization is located.

7. `addressLocality`: The locality or city where the organization is located.

8. `addressCountry`: The country where the organization is located.

9. `contactCompanyProfileHref`: The URL link to the company profile.

10. `industryNaicsTwoCodes`: The NAICS (North American Industry Classification System) code at the two-digit level associated with the organization.

11. `industryUrls`: A list of industry URLs associated with the organization. Each entry in the list contains a description and a URL.

12. `industryNaicsFourCodes`: A list of NAICS codes at the four-digit level associated with the organization.

13. `searchCandidates`: A list of search candidates matching the given criteria. Each entry in the list contains the display sequence and contact details.

14. `telephoneNumber`: The telephone number of the contact person.

15. `organization`: Information about the organization associated with the contact person. It includes the primary name, telephone number, street address, postal code, region, locality, and country.

16. `usSicV4Description`: The description of the US SIC (Standard Industrial Classification) code associated with the organization.

Note: The values associated with each field in the JSON data were not provided, so the documentation focuses on explaining the purpose and meaning of each field rather than their specific values.


## What is Dun & Bradstreet?
Dun & Bradstreet is a leading global provider of business data and insights. They offer a vast database containing detailed information on millions of companies worldwide, including company profiles, financials, industry analysis, key personnel, and more. This data can be invaluable for various purposes such as market research, lead generation, competitor analysis, and risk assessment.

## How Does the Apify Actor Work?
The Apify Actor for Dun & Bradstreet leverages the Apify platform's capabilities to automate the process of gathering data from D&B. It uses web scraping techniques to navigate D&B's website, search for specific companies or individuals, and extract the relevant data fields. The actor is equipped with intelligent algorithms to handle various data structures and deliver the extracted data in a structured format for further analysis.


### **Benefits of Using the Apify Actor**

Utilizing the Apify Actor for Dun & Bradstreet offers several advantages:

1. **Time and Effort Savings**: Manually collecting data from Dun & Bradstreet can be a laborious task. The Apify Actor automates the process, significantly reducing the time and effort required.

2. **Accurate and Reliable Data**: The actor ensures that the extracted data is accurate and up-to-date, providing you with reliable information for your business needs.

3. **Scalability**: The Apify platform allows you to scale your data extraction tasks easily. Whether you need to extract data for a few companies or thousands, the actor can handle the workload efficiently.

4. **Customizable Data Extraction**: The actor allows you to specify the advanced search filter you require, tailoring the extraction process to your specific needs. This flexibility ensures that you only get the data that is relevant to your business.


### **Use Cases of Dun & Bradstreet Data scraper**

The Dun & Bradstreet data extracted through the Apify Actor can be utilized in various ways:

1. **Sales and Marketing**: Identify and target potential leads based on specific criteria such as industry, location, or company size or job title

## How much will it cost me to scrape dnb.com ?
To use this scraper you need to pay $25 per month fixed cost to the developer and you should have an [Apify subscription](https://apify.com/pricing) which starts from $49/mo prepaid usage credits. 
Based on historical data our scraper costs an average of $1 per thousand records scraped as usage credits.
Based on above data, you can scrape upto 49000 records per month with starter plan

## Is it legal to scrape dnb.com ?
Our scrapers are ethical and do not extract any private user data, such as email addresses, gender, or location. They only extract what the user has chosen to share publicly. We therefore believe that our scrapers, when used for ethical purposes by Apify users, are safe. 
However, you should be aware that your results could contain personal data. Personal data is protected by the [GDPR](https://docs.apify.com/academy/get-most-of-actors/actor-readme#:~:text=protected%20by%20the-,GDPR,-in%20the%20European) in the European Union and by other regulations around the world. 
You should not scrape personal data unless you have a legitimate reason to do so. If you're unsure whether your reason is legitimate, consult your lawyers. You can also read our blog post on the [legality of web scraping](https://blog.apify.com/is-web-scraping-legal/)

## Your feedback
We’re always working on improving the performance of our Actors. So if you’ve got any technical feedback for DNB Scraper or simply found a bug, please create an issue on the actor’s [Issues](https://console.apify.com/actors/fXblzs6QLMDumpdI9/issues) tab in Apify Console.
