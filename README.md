# Start Prometheus
./start.sh or docker-compose up -d

# Configure
1. Prometheus
 - configure files : ./prometheus/promethues.yml
 - alert rule files : ./prometheus/rules.yml
2. Grafana
 - set the password : ./grafana/config.monitoring
3. alertmanager
 - set the slack_api_url : ./alertmanager/config.yml
