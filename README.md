# splunk_ip_sighting

Populating KVstore lookup _sighting_ip_ with ip sighting from network traffic

Two scheduled saved searches run every hour to keep updated KV store lookup with
* ip
* count
* first_seen
* last_seen

Based on ES Datamodel Network Traffic
