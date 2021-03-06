CodeIgniter IP2Location Library
===============================

Installation
------------
Upload `controllers` and `libraries` to CondeIngniter `application` folder.


Usage
-----
Use following codes in your application for get geolocation information.

    // Define IP2Location database path
    define('IP2LOCATION_DATABASE', '/path/to/ip2location/database');

    $this->load->library('ip2location_lib');
    $countryCode = $this->ip2location_lib->getCountryCode('8.8.8.8');


Methods
-------
    $countryCode = $this->ip2location_lib->getCountryCode($ip);
    $countryName = $this->ip2location_lib->getCountryName($ip);
    $regionName = $this->ip2location_lib->getRegionName($ip);
    $cityName = $this->ip2location_lib->getCityName($ip);
    $latitude = $this->ip2location_lib->getLatitude($ip);
    $longitude = $this->ip2location_lib->getLongitude($ip);
    $isp = $this->ip2location_lib->getISP($ip);
    $domainName = $this->ip2location_lib->getDomainName($ip);
    $zipCode = $this->ip2location_lib->getZIPCode($ip);
    $timeZone = $this->ip2location_lib->getTimeZone($ip);
    $netSpeed = $this->ip2location_lib->getNetSpeed($ip);
    $iddCode = $this->ip2location_lib->getIDDCode($ip);
    $areaCode = $this->ip2location_lib->getAreaCode($ip);
    $weatherStationCode = $this->ip2location_lib->getWeatherStationCode($ip);
    $weatherStationName = $this->ip2location_lib->getWeatherStationName($ip);
    $mcc = $this->ip2location_lib->getMCC($ip);
    $mnc = $this->ip2location_lib->getMNC($ip);
    $mobileCarrierName = $this->ip2location_lib->getMobileCarrierName($ip);
    $elevation = $this->ip2location_lib->getElevation($ip);
    $usageType = $this->ip2location_lib->getUsageType($ip);