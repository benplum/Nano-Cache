# Nano-Cache

Pico Plugin for handling page caching. 

### Installation

Start by moving the <code>plugins/nano_cache.php</code> file into your existing Pico install. Then simply configure the caching options. 

### Configuration

	$config["nano_cache"] = array(
		"enabled" => false,		// Flag to enable caching
		"time" => 604800		// Cache duration
	);