# Postman & Newman Integration for TMDB(The Movie Database)

This repository provides a structured approach for QA testing of The Movie Database (TMDB) API using Postman and Newman. The goal is to ensure comprehensive coverage of API functionalities, including data retrieval, authentication, and error handling.

## Prerequisites
1. **Postman Installed:** Download from [Postman](https://www.postman.com/).
2. **Node.js Installed:** Download from [Node.js](https://nodejs.org/tr)
3. **Newman Installed:** Install via npm:
   ```bash
   npm install -g newman
   ```
4. **API Keys:** Ensure you have a valid TMDB API key for testing.

### Setting Up the API Key
- Obtain your API key from [TMDB API Key Settings](https://www.themoviedb.org/settings/api).
- Add the API key to your Postman environment:
  1. Go to **TMDB_ENV_VARIABLES** in Postman.
  2.  Edit the environment
  3.  Assign your own APIKey to the "apiKey" variable in the environment than save the changes


## Steps to Use

### 1. Clone the Repository
```bash
git clone https://github.com/ezginacar/TMDB-Postman-API-Test.git
```

### 2. Import Postman Collection
- Open Postman.
- Go to **File > Import**.
- Select `TMDB.postman_collection.json`.

### 3. Run Tests with Collection Runner,
- Make sure the "TMDB Test Datas.csv" file is added at the Collection Runner
- Execute individual requests or the entire collection.


## Reporting
- Newman generates JSON reports stored in the `Newman_Reports` directory.

