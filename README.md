SFDR Periodic Disclosures for Article 8 and 9 Funds - MSCI Mapping

We are going to explore how to automate the process of ingesting MSCI Data into an Excel with Power Query and transforming the data into the data points that correspond to the fields in ESG Annex.
There is a requirement to calculate the data points at 2 levels:
- issuer
- fund level

The Delegated Regulation (EU) 2023/363 pertains to the content and presentation of information about financial products for investment in environmentally sustainable economic activities. It requires regular disclosure in pre-contractual documents and annual reports.

The ESG Annex refers to the disclosure of environmental, social, and governance (ESG) metrics for financial products. Let’s break it down:

1. Benchmark Regulation Metrics:
These metrics align with the Commission Delegated Regulation (EU) 2020/1816. They provide ESG information in benchmark statements, reflecting how ESG factors impact each benchmark.
The regulation specifies mandatory and voluntary ESG metrics based on the underlying assets (e.g., equity, fixed income) of the indexes. 
2. EU Sustainable Finance Disclosure Regulation (SFDR) Metrics:
These metrics comply with the SFDR requirements. They include select ESG metrics outlined in the regulatory technical standards.
SFDR aims to enhance transparency by disclosing ESG information related to financial products1.
3. Other Index-Level ESG Metrics:
Beyond SFDR and the Benchmark Regulation, there are additional ESG metrics.
MSCI Limited, for instance, provides ESG metrics for its indexes, but it’s not a “financial market participant” as defined in the regulations1.
As for calculation and creation, methodologies vary across index providers. They map sectors, use data, and apply formulas to calculate ESG scores.
