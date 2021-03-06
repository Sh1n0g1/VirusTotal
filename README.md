# [VirusTotal] Maltego Local Transforms
Maltego Local Transforms to use VirusTotal Private API - https://www.virustotal.com/en/documentation/private-api/

# Prerequisites
- VirusTotal Private API access
- Python 2.7.x

# Setup
- Edit VT.py and set "apikey" variables with your API key.
- Put VT.py and MaltegoTransform.py into your working directory. (e.g. C:\Maltego\Transforms\VirusTotal)
- Open VT.mtz to import Maltego configuration.
- The current configuration uses the following directories, so you may have to change them according to your environment.  
  Command line = C:\Python27\python.exe  
  Working directory = C:\Maltego\Transforms\VirusTotal

# Transforms
- c2host_to_hash
- host_to_downloadedhash
- c2ip_to_hash
- ip_to_downloadedhash
- domain_to_ip
- ip_to_domain
- hash_to_c2host
- hash_to_c2ip
- hash_to_c2url
- hash_to_avdetection
- hash_to_filename
- hash_to_useragent
- hash_to_imphash
- hash_to_similar
- useragent_to_hash
- imphash_to_hash
- hash_to_rescan
- hash_to_section
- hash_to_timestamp
- hash_to_firstseen
- hash_to_filesize
- hash_to_filetype
- hash_to_peresource
- hash_to_itw
- hash_to_mutex
- hash_to_md5
- hash_to_sha256
- section_to_hash
- mutex_to_hash
- peresource_to_hash
- hash_to_detectratio
- url_to_detectratio
- domain_to_detectedurl
- ip_to_detectedurl
- domain_to_subdomain
- hash_to_import
- import_to_hash
- hash_to_tag
- hash_to_behaviour / Beta
- behaviour_to_hash / Beta




