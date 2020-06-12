from urllib.parse import urlparse

def domain_name(url):
    if 'http' in url:
        host = urlparse(url).netloc
        host = host.split('.')
        if 'www' in host:
            return host[1]
        else:
            return host[0]
    elif 'www' in url:
        host = url.split('.')
        return host[1]
    else:
        host = url.split('.')
        return host[0]
