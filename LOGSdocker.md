Traceback (most recent call last):
File "urllib3/connectionpool.py", line 670, in urlopen
File "urllib3/connectionpool.py", line 392, in _make_request
File "http/client.py", line 1255, in request
File "http/client.py", line 1301, in _send_request
File "http/client.py", line 1250, in endheaders
File "http/client.py", line 1010, in _send_output
File "http/client.py", line 950, in send
File "docker/transport/unixconn.py", line 43, in connect
FileNotFoundError: [Errno 2] No such file or directory

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
File "requests/adapters.py", line 439, in send
File "urllib3/connectionpool.py", line 726, in urlopen
File "urllib3/util/retry.py", line 410, in increment
File "urllib3/packages/six.py", line 734, in reraise
File "urllib3/connectionpool.py", line 670, in urlopen
File "urllib3/connectionpool.py", line 392, in _make_request
File "http/client.py", line 1255, in request
File "http/client.py", line 1301, in _send_request
File "http/client.py", line 1250, in endheaders
File "http/client.py", line 1010, in _send_output
File "http/client.py", line 950, in send
File "docker/transport/unixconn.py", line 43, in connect
urllib3.exceptions.ProtocolError: ('Connection aborted.', FileNotFoundError(2, 'No such file or directory'))

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
File "docker/api/client.py", line 214, in _retrieve_server_version
File "docker/api/daemon.py", line 181, in version
File "docker/utils/decorators.py", line 46, in inner
File "docker/api/client.py", line 237, in _get
File "requests/sessions.py", line 543, in get
File "requests/sessions.py", line 530, in request
File "requests/sessions.py", line 643, in send
File "requests/adapters.py", line 498, in send
requests.exceptions.ConnectionError: ('Connection aborted.', FileNotFoundError(2, 'No such file or directory'))

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
File "docker-compose", line 3, in <module>
File "compose/cli/main.py", line 81, in main
File "compose/cli/main.py", line 200, in perform_command
File "compose/cli/command.py", line 60, in project_from_options
File "compose/cli/command.py", line 152, in get_project
File "compose/cli/docker_client.py", line 41, in get_client
File "compose/cli/docker_client.py", line 170, in docker_client
File "docker/api/client.py", line 197, in __init__
File "docker/api/client.py", line 221, in _retrieve_server_version
docker.errors.DockerException: Error while fetching server API version: ('Connection aborted.', FileNotFoundError(2, 'No such file or directory'))
[1097] Failed to execute script docker-compose
