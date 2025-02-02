import React from 'react';

function App() {
  return (
    <div style={styles.container}>
      <div style={styles.welcome}>WELCOME</div>
      <div style={styles.chooseLanguage}>Choose the language</div>
      <div style={styles.languageButtons}>
        <a
          href="https://tally.so/r/wo5DR1"
          style={styles.languageButton}
        >
          العربية
        </a>
        <a
          href="https://tally.so/r/w7adg6"
          style={styles.languageButton}
        >
          Français
        </a>
      </div>
    </div>
  );
}

const styles = {
  container: {
    fontFamily: 'Arial, sans-serif',
    display: 'flex',
    justifyContent: 'center',
    alignItems: 'center',
    height: '100vh',
    flexDirection: 'column',
    backgroundColor: '#f4f4f4',
  },
  welcome: {
    fontSize: '2.5em',
    marginBottom: '20px',
  },
  chooseLanguage: {
    fontSize: '1.2em',
    marginBottom: '20px',
  },
  languageButtons: {
    display: 'flex',
    gap: '20px',
  },
  languageButton: {
    padding: '10px 20px',
    fontSize: '1em',
    color: 'white',
    backgroundColor: '#007BFF',
    border: 'none',
    borderRadius: '5px',
    cursor: 'pointer',
    textDecoration: 'none',
  },
};

export default App;
