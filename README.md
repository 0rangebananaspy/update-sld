# update-sld
Update insiden untuk monitoring Status Layanan Digital (SLD)

# How To Update Incident
1. Edit file incidents.txt
2. Add new line at the very top with appropriate description. You can add estimate time needed to solve the new incidents. Optional but very important to add your nickname.
3. Commit the changes.
4. Ansible agent will recognize your changes and immediately pull the repo then deploy source code to Firebase.

# How to Update Host or Domain to monitor
1. Edit file checks.csv
2. Add your host or domain.
3. Use http protocol for domain record. Use ping protocol for server or private domain.
4. Commit the changes.
