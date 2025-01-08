## Evaluation Overview

The evaluation was conducted using a test sample comprising all 26 issues of the **Le Sémaphore de Marseille** from January 1895. The scanned documents for this month are available through the BNF's dedicated newspapers website: [BNF Newspaper Archive](https://tinyurl.com/2yutsn2m).

### Extracted Data

The produced CSV file contains ship arrival data extracted from the "ARRIVÉE" section of the newspaper. Specifically, for each ship arrival, the following data is extracted:

- **Port of Origin**:  
  Usually appears at the start of the paragraph.

- **Date of Departure from Origin**:  
  Always appears after the port of origin and consists of a number and a month or the word "cour."

- **Port and Date of Call**:  
  Any intermediate stops made by the ship on its journey to the final destination and the date of departure from the port of call.

- **Ship Type**:  
  Found in lowercase and in abbreviation form (e.g., "vap," "br," "br-goel," "bat," etc.).

- **Ship’s Flag**:  
  Found in lowercase (e.g., "grec" for Greek).

- **Ship Name**:  
  Usually appears after the ship’s flag.

- **Ship Tonnage**:  
  If it exists, it appears after the name of the ship and usually starts with "de."

- **Name of Captain**:  
  Usually starts with "cap" or "c."

- **Cargo Information**:  
  Usually starts with "avec" and includes cargo quantity, unit of measurement, and type of cargo.

- **Consignee of Cargo**:  
  If it exists, it is always after the cargo information and usually starts with "pour" or "p."

- **Consignee of Ship**:  
  Usually appears after the cargo information but can also be absent. Typically begins with terms like "le navire," "nav," "navire," or may simply be a name or entity.

- **Intelligence**:  
  Includes events or interactions during the journey, such as passing the Strait of Gibraltar, passenger information, etc.; always appears last if it exists.

