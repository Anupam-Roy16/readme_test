
## Installation

1. Clone the repository:
   ```bash
   git clone [your-repository-url]
   git pull
   git stash -m dummy
   git checkout
   ll
   ```

2. Run setup.py and Install required packages:
   ```bash
    pip install -e .
   ```

3. Upload credentials file in `dev02` folder:

4. Create a ".env" named file in bot folder:
   ```python
    BOT_SESSION_NAME=Guru_Sevak
    CREDENTIAL_FILE="your creadentials file path"
    SQ_COLLECTION_ROOT_FOLDER=1QzOdJnqJGdk7SOm3fNfUZGHlafwFeRSD
    SUDO_EMAILS=anikpaul.eee.buet@gmail.com

    SHAON=6945810550
    SQBOT=7846627409
    ANANTASESA=8014919442

    CHAT_SELECTION=-1002310525868
    CHAT_COLLECTION=-1002311798167
    TABLE_DIR="your tables folder path"

    # database
    USER=postgres
    PASSWORD="your-password"
    PORT=5432
    DATABASE=sq_db
    HOST=localhost
    SCHEMA_NAME=sq_db_test
    LOGS_DIR="your logs foder path"
    
5. Set up PostgreSQL database:
  - Make sure PostgreSQL is installed and running
6. Initialize the database:
   ```bash
   python Initialize_system.py
   ```
7. After database setup is complete, start the bot:
   ```bash
   python run_bot.py
   ```
   
   ⚠️ Important: 
   - Never run the program by more than one user simultaneously


