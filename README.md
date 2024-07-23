# APISecurityEngine CLI Agent (Traffic Capture)

This CLI agent captures API traffic and sends it to the APISecurityEngine for analysis.

## Prerequisites

Ensure you have Python 3.6 or higher installed on your system.

## Installation

1. Clone this repository or download the `apisecengine-cli-agent.py` file.

2. Install the required Python modules:

   pip install requests

## Usage

Run the script using the following command:

   python3 apisecengine-cli-agent.py --api_key=YOUR_API_KEY --host=HOST --port=PORT

### Parameters

- `--api_key`: Your APISecurityEngine API key (required)
- `--host`: The host address of the APISecurityEngine server (default: localhost)
- `--port`: The port number of the APISecurityEngine server (default: 5002)

### Example

   python3 apisecengine-cli-agent.py --api_key=8FRAOGSIPHS6KYWFKTY7 --host=localhost --port=5002

This command will start the CLI agent, which will capture API traffic and send it to the APISecurityEngine server running on `localhost:5002` using the provided API key.

## Notes

- Ensure that you have the necessary permissions to capture network traffic on your system.
- The script uses `subprocess` to run system commands, so it may require elevated privileges depending on your operating system.

For more information or support, please contact the APISecurityEngine team.
