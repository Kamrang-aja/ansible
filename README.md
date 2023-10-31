# ANSIBLE

Noted direktory:  
- playbooks/: Ini adalah direktori di mana Anda menyimpan playbook Ansible Anda. Playbook adalah file YAML yang berisi tugas-tugas yang akan dijalankan pada host.  

- inventory/: Ini adalah direktori di mana Anda menyimpan file inventory Ansible. Inventory berisi daftar host yang akan dikelola oleh Ansible.  

- group_vars/: Jika Anda ingin mengatur variabel yang berkaitan dengan grup host tertentu, Anda dapat meletakkannya di sini.  

- roles/: Ini adalah direktori di mana Anda dapat menyimpan peran Ansible yang dapat digunakan kembali. Setiap peran memiliki struktur direktori yang terorganisir dengan baik.  

- files/: Jika Anda perlu mengunggah file ke host, Anda dapat meletakkannya di sini, dan playbook dapat mengaksesnya.  

- templates/: Jika Anda ingin menggunakan file template Jinja2 dalam playbook Anda, Anda dapat meletakkannya di sini.  

- ansible.cfg: Ini adalah file konfigurasi Ansible yang mengatur pengaturan Ansible secara global.  
