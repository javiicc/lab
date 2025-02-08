# Reload systemd to recognize the new service
sudo systemctl daemon-reload

# Enable the service (so it starts on boot)
sudo systemctl enable day-and-night.service

# Start the service immediately
sudo systemctl start day-and-night.service
