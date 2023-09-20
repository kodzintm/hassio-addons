# Home Assistant Community Add-on: TVHeadend

TVHeadend jest serwerem do strumieniowania i nagrywania TV. Współpracuje z sytemami:
DVB-S, DVB-S2, DVB-C, DVB-T, DVB-T2, ATSC, ISDB-T, IPTV, SAT>IP, HDHomeRun.

## Instalacja

1. Dodaj to repozytorium do HA:
   [![Home Assistant with repository URL pre-filled][my-ha-shield]][my-ha-repo]
2. Wyszukaj "TVHeadend" add-on na liście i zainstaluj.
3. Uruchom "TVHeadend" add-on.

- Pliki konfiguracujne: `/config/tvheadend/`
- Nagrania: `/config/tvheadend/recordings/`

Poprowione mapownie:
  - /dev/dvb/adapter0/demux0
  - /dev/dvb/adapter0/dvr0
  - /dev/dvb/adapter0/frontend0
  - /dev/dvb/adapter0/net0
  - /dev/dri

## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[alpine-packages]: https://pkgs.alpinelinux.org/packages
[forum]: https://community.home-assistant.io/
[frenck]: https://github.com/frenck
[gautham]: https://github.com/GauthamVarmaK
[kodzin]: https://github.com/kodzintm
[my-ha-shield]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
[semver]: http://semver.org/spec/v2.0.0.htm
[my-ha-repo]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fkodzintm%2Fhassio-addons
[releases]: https://github.com/kodzintm/addon-tvheadend/releases
