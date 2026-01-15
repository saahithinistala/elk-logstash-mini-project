ELK Logstash Mini Project

This project parses application logs using Logstash.

Parsed fields:
- log_time
- level
- app
- user
- endpoint
- txnId
- latency_ms
- msg
- reason (optional)

Tags:
- alert (ERROR logs)
- slow_call (latency > 1000ms)

How to run:
logstash -f logstash.conf
