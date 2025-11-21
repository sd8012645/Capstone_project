We use three openly available email–spam corpora:

  1-Enron Spam Data (Kaggle, marcelwiechmann) – main dataset-https://www.kaggle.com/datasets/marcelwiechmann/enron-spam-data

  2- Spam Email Dataset (Kaggle, jackksoncsie)-https://www.kaggle.com/datasets/marcelwiechmann/enron-spam-data

  3-Email Spam Classification (HuggingFace, UniqueData)- https://huggingface.co/datasets/UniqueData/email-spam-classification

**Summary:**

We use three open datasets for email spam classification. Our main corpus is the Enron Spam Data from Kaggle, which is a single CSV combining the six Enron‑Spam datasets introduced by Metsis et al. (CEAS 2006) and built from real Enron mailboxes plus injected spam from external sources. As a second dataset we use Kaggle’s Spam email Dataset (emails.csv), a 5,728‑message corpus originally assembled for MITx’s Analytics Edge course, where non-spam(ham) messages come from Enron executive Vincent Kaminski’s inbox and spam comes from the SpamAssassin public corpus and Project Honey Pot, with roughly a 75/25 ham–spam split. Finally, we include the UniqueData email‑spam‑classification dataset from HuggingFace, a small (84‑email) vendor‑curated sample of English emails labeled as spam or not spam, provided under a CC BY‑NC‑ND 4.0 license as an example of the commercial datasets offered by the vendor.

**Enron Spam Data Properties**

CSV file contains:

Subject – email subject line (string)

Message – full email body text (string)

Spam/Ham – label string with values "spam" or "ham"

Date – date/time string parsed from the original headers

Key characteristics:

Scale: ~33k emails.

Labels: near‑balanced ham vs. spam.

Domain: business emails between Enron employees plus real‑world spam messages from the early 2000s, making this a widely used benchmark for content‑based spam filtering.
