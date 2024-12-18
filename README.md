notes

```bash
curl -X 'POST' \
  'https://api.educoding.id/dataofdevice' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{ \
  "device_id": "0e96b39f-cf6b-415d-9778-faf29091b3db", \
  "application_id": "8488c15c-eb9f-47ac-9427-bfa79006cba7", \
  "data": [ \
    { \
      "id": 3173, \
      "attributes": { \
        "createdAt": "2024-05-21T05:35:57.918Z", \
        "updatedAt": "2024-05-21T05:35:57.918Z", \
        "publishedAt": "2024-05-21T05:35:57.915Z", \
        "dist": 9, \
        "vol": 315, \
        "capacity": 89, \
        "tegangan": 11.74, \
        "daya": 1346, \
        "arus": 114.7, \
        "event": "DataUpdate", \
        "sensor_id": "1", \
        "battPercent": 30.47618, \
        "konstantaPembagi": 1, \
        "ina219_avail": true \
      }, \
}, \
  ] \
}'

```
