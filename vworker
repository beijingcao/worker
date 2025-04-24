export default {
  async fetch(request, env) {
    const url = new URL(request.url);
    url.host = 'v.hwmind.com';
    return fetch(new Request(url, request))
  }
}
