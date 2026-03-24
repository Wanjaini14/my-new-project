<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# AI accountant

Final project for the Building AI course

## Summary

An AI-powered accountant that incorporates Kirjanpitolautakunta (KILA) guidance and Finnish tax laws to provide accurate, real-time bookkeeping and tax advice. It helps businesses and individuals ensure compliance, automate financial reporting, and reduce errors in accounting and taxation


## Background

Accounting and taxation in Finland are complex and require constant attention to changing laws and official guidance. Many small businesses and freelancers struggle with bookkeeping, compliance, and reporting, often leading to costly mistakes or the need for expensive professional services.
Manual bookkeeping is time-consuming and error-prone
Understanding Finnish tax laws and KILA guidance is difficult for non-experts
Small businesses cannot always afford professional accountants
Regulations change frequently, making it hard to stay up to date
This idea is important because improving access to reliable accounting support can save time, reduce stress, and help businesses operate more efficiently and legally.


## How is it used?

The AI accountant would be used through a web or mobile application.
Typical usage:
The user uploads receipts, invoices, or financial data
The AI categorizes transactions automatically
It provides real-time suggestions for bookkeeping entries
The user can ask questions (e.g. “Is this deductible?”)
The system generates reports (tax reports, financial statements)
Users:
Small business owners
Freelancers
Startups
Individuals managing personal finances
The system should be easy to use, reliable, and provide clear explanations — not just answers.



This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods

The system would use data from Finnish tax authority guidelines, Kirjanpitolautakunta (KILA) recommendations, public accounting standards, and sample financial datasets. It would also rely on user-provided data such as receipts, invoices, and transaction histories.
The AI methods would include natural language processing to understand user questions, classification models to categorize transactions, rule-based systems to follow tax and accounting rules, and machine learning to improve performance over time. Optical character recognition could be used to extract data from receipts and documents.

## Challenges

One of the main challenges is ensuring full legal accuracy, since mistakes could have financial consequences. The system must also stay updated with changing laws and regulations. Handling sensitive financial data securely is critical, and the system must protect user privacy. Another challenge is making the AI explain its decisions clearly so users can trust it. There is also a risk that users rely too heavily on the AI instead of seeking professional advice when needed.

## What next?

This project could be expanded by integrating it with banking systems and accounting software, allowing automatic data syncing. It could also provide real-time tax optimization suggestions and support multiple countries. A chatbot interface could make interaction more natural, and a working prototype could be developed using real datasets.
To move forward, more knowledge of Finnish accounting rules would be needed, along with access to real financial data and programming skills in machine learning. Collaboration with accounting professionals would also help improve accuracy and usability.


## Acknowledgments

* This project is inspired by Finnish Tax Administration guidelines, Kirjanpitolautakunta (KILA) recommendations, and the Elements of AI course.
