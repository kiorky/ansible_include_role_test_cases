# Alternate test case for #35065

## 2.4
```
changed: [localhost] => {"changed": true, "cmd": "whoami", "delta": "0:00:00.004153", "end": "2018-02-14 18:46:52.763540", "failed": false, "rc": 0, "start": "2018-02-14 18:46:52.759387", "stderr": "", "stderr_lines": [], "stdout": "kiorky", "stdout_lines": ["kiorky"]}
changed: [localhost] => {"changed": true, "cmd": "whoami", "delta": "0:00:00.002497", "end": "2018-02-14 18:46:52.978556", "failed": false, "rc": 0, "start": "2018-02-14 18:46:52.976059", "stderr": "", "stderr_lines": [], "stdout": "root", "stdout_lines": ["root"]}
changed: [localhost] => {"changed": true, "cmd": "whoami", "delta": "0:00:00.002467", "end": "2018-02-14 18:46:53.177610", "failed": false, "rc": 0, "start": "2018-02-14 18:46:53.175143", "stderr": "", "stderr_lines": [], "stdout": "root", "stdout_lines": ["root"]}
```

## 2.5

```
changed: [localhost] => {"changed": true, "cmd": "whoami", "delta": "0:00:00.005728", "end": "2018-02-14 18:49:16.093737", "failed": false, "rc": 0, "start": "2018-02-14 18:49:16.088009", "stderr": "", "stderr_lines": [], "stdout": "kiorky", "stdout_lines": ["kiorky"]}
changed: [localhost] => {"changed": true, "cmd": "whoami", "delta": "0:00:00.003229", "end": "2018-02-14 18:49:16.462346", "failed": false, "rc": 0, "start": "2018-02-14 18:49:16.459117", "stderr": "", "stderr_lines": [], "stdout": "kiorky", "stdout_lines": ["kiorky"]}
changed: [localhost] => {"changed": true, "cmd": "whoami", "delta": "0:00:00.003650", "end": "2018-02-14 18:49:16.847442", "failed": false, "rc": 0, "start": "2018-02-14 18:49:16.843792", "stderr": "", "stderr_lines": [], "stdout": "kiorky", "stdout_lines": ["kiorky"]}
```
