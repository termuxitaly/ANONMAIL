# 🌐 ANONMAIL SENDER

- [ ] Install Git and Python  
  
sh
  pkg install git && pkg install python
 
  <button onclick="copyToClipboard('pkg install git && pkg install python')">Copia</button>

- [ ] Update and upgrade packages  
  
sh
  pkg update && pkg upgrade
 
  <button onclick="copyToClipboard('pkg update && pkg upgrade')">Copia</button>

- [ ] Clone the repository  
  
sh
  git clone https://github.com/termuxitaly/ANONMAIL && cd ANONMAIL
 
  <button onclick="copyToClipboard('git clone https://github.com/termuxitaly/ANONMAIL && cd ANONMAIL')">Copia</button>

- [ ] Install requirements  
  
sh
  pip install -r requirements.txt
 
  <button onclick="copyToClipboard('pip install -r requirements.txt')">Copia</button>

- [ ] Make the script executable  
  
sh
  chmod +x anonsender.pyc
 
  <button onclick="copyToClipboard('chmod +x anonsender.pyc')">Copia</button>

- [ ] Run the script  
  
sh
  python anonsender.pyc
 
  <button onclick="copyToClipboard('python anonsender.pyc')">Copia</button>

<script>
  function copyToClipboard(text) {
    navigator.clipboard.writeText(text).then(function() {
      console.log('Copiato negli appunti:', text);
    }, function(err) {
      console.error('Errore nel copiare il testo: ', err);
    });
  }
</script>

# 🥷 questo script fornisce un'interfaccia intuitiva per configurare, gestire e inviare email in modo anonimo utilizzando un server SMTP specificato e personalizzato, con supporto per allegati e opzioni avanzate di formattazione del messaggio.