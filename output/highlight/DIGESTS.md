## Subresource Integrity

If you are loading Highlight.js via CDN you may wish to use [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) to guarantee that you are using a legimitate build of the library.

To do this you simply need to add the `integrity` attribute for each JavaScript file you download via CDN. These digests are used by the browser to confirm the files downloaded have not been modified.

```html
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.10.0/highlight.min.js"
  integrity="sha384-pGqTJHE/m20W4oDrfxTVzOutpMhjK3uP/0lReY0Jq/KInpuJSXUnk4WAYbciCLqT"></script>
<!-- including any other grammars you might need to load -->
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.10.0/languages/go.min.js"
  integrity="sha384-Mtb4EH3R9NMDME1sPQALOYR8KGqwrXAtmc6XGxDd0XaXB23irPKsuET0JjZt5utI"></script>
```

The full list of digests for every file can be found below.

### Digests

```
sha384-qimhSkVWof5rfaFajQk8KAtzSRYyIArcJCMKWdDcNq34F4uplk08wmEyUiYLmO+3 /es/languages/c.js
sha384-5fESKgrRcGs7I/89bn7NKFcHyvIVcmQIG4JfCEAV5Rg5VVtskrmGkHVOIsD1642v /es/languages/c.min.js
sha384-xjI3wQy5aAhTr4JT9bE8tZaEMtNn/fguEQOem1vG04xZl4Ov0uf8bsLkQUoUzvbo /es/languages/cmake.js
sha384-JdSkDmOvEqN4fTPk/zl0QpN/wGh53J+xJRFtOMdEwhZ2iDgT5a/Dl18e/TChDqjK /es/languages/cmake.min.js
sha384-eM9Op3b0ilZ/iW7jeVAMo//MKcEXHCbg1Vf8SMrqds5LIOeF9+3qaX//TsnbItae /es/languages/cpp.js
sha384-+tDHTmLKfBxXgVksRhLEJM4z9PfcGQ2XsrZMDcdJ1SIlPZrtAR4+m4XUX+zJf5nf /es/languages/cpp.min.js
sha384-lU6If27eTyL2Yr+WS3ErF0/raeRKUheLuCM44IUaUshDCTvTeQijobPXY4wgkDGb /es/languages/csharp.js
sha384-k4z6XdU7qI35NxUF8SGumv5kMerrVg/xoat0iSaWnu/dHKoNZKdxZN3gI2WYgMfe /es/languages/csharp.min.js
sha384-DRSBRBp34y5KixP9TEkoyASphUQfWiiqtSP20YveUIY05CjkoCG1wOe8A1cfMIZT /es/languages/glsl.js
sha384-0QXwzWESgZAQ8866ALLJEDZ9l14HhJTWnECXBxJ4DHDmywVn0LRIMqz7JJQWG/AM /es/languages/glsl.min.js
sha384-ZCfS+s/zxY7O2bm2KoVJo1wUrLEpJDHZAi/LJAdJF5XjnfSWICkg6wHd2SEJGpyR /es/languages/java.js
sha384-716dHwZ7zbZcnEwTe7DLxlm5tH3Iyl8vSW5a2kYPgusEdp5k3A3jeZt0Ck+CjYE0 /es/languages/java.min.js
sha384-oQpcUGMBf+VDTHOLQ1uhPp1FgNBo0OZc9gbXGuVFwAogHlkh/Iw6cvKKgcgCQkmV /es/languages/javascript.js
sha384-3T8DJ91yCa1//uY9h8Bo4QLrgEtbz4ILN2x9kSM4QWX9/1kKu6UXC3RAbVQV85UQ /es/languages/javascript.min.js
sha384-R87hRh4kF8+iz2sB6FvLrfR0XZBohjFXeJKIXld1Eji2UVi+M2+OIgJKma/9Ko6u /es/languages/json.js
sha384-QFDPNpqtrgZCuAr70TZJFM4VCY+xNnyGKwJw2EsWIBJOVcWAns9PHcLzecyDVv+x /es/languages/json.min.js
sha384-OJrXTVCemUa68axskWVxZHXuDfyPWWFK0X2cJsPaMBt6jGY1HxnBZJVPEHTqou4H /es/languages/lua.js
sha384-cjlU8DPjZ3XY/dLzIx+CaoB2jzKXf43s2KSU2rZQGmxwR1d7k9p+SFt1IsNkFnnV /es/languages/lua.min.js
sha384-npg+R4K6p4Q5dEzYDKy3gZ+l4mGV8hDMErOZdSSvqLxED30Fhmgb54WD4wkeY5yh /es/languages/makefile.js
sha384-Ev1PV0+HiSwEbi0IfJYmpMoxv3E0sWhAALg1frIiitM9zh2BVDe871H9Z/RGXqFM /es/languages/makefile.min.js
sha384-e+d8RFZbtc5Pmt3xfX9uuElm63v5qOj7T5hAkkFbnYc1wEk7wCLlzOsm66MCf5Uk /es/languages/python.js
sha384-CPHh+9FxkWF3OtMZdTj5oQN1Qti0p4/5XBABz/JdgssOKHmfAOFz6Gu4tsG6MQiH /es/languages/python.min.js
sha384-LZ+YGF0Xve9sHzC9G37Kc14gDC6lfDpny2hggVJVfHb+OsTEXgMGLmAWUJzi4YRC /es/languages/rust.js
sha384-/ktfWRgwL+kZAZeeXDl9mwkD/3atjwjkzLCCoSHtME7MzP87wMhUmNUZ83AoqYx2 /es/languages/rust.min.js
sha384-WHdxyD51Y+ytDdcYGVkKHQOThUwwhLl/1GvZxHTHL4ImI4NS32L/B8bvB/1zN/Mk /languages/c.js
sha384-jtwnwOYA+K4zYN55fA4z4U0PTK5oEp4RcLYaXkYRKO3UUzge1o21ArmvKmTRdh/d /languages/c.min.js
sha384-gXeNvrs51WLYPI/WV54m5BSGtmPSOkEngcs0hrofwSIZ+uVCXW6SwnU75AWUpsiH /languages/cmake.js
sha384-NXUiKRE4iB8J7h3t1Z2aLjDRJslCWi4SWqJpec1z0Y927kNqWejg1uGaEh1P3GCK /languages/cmake.min.js
sha384-M2wpTxQe2N0750xYZ0zTinwbmjsZjdtuS7twUUP2dxtHR0YqhY3JuUFyyhANf9Uy /languages/cpp.js
sha384-/yf54L01PbO6NtVs1Pu9rgfNHbKXanLdNcGVuNa0m5+KiyH+1NpZRDK6idm5VoVl /languages/cpp.min.js
sha384-73x+NDGuWTdFik2BOd5uwmBcikSmR+Qx5AVbJLifM/M0hBbwKToQ45xBWxKYkpgd /languages/csharp.js
sha384-6NsOlZtv7W2iSoDU+Yi+hENfl3MuiECvnl7emdRUvpIpDbLvoCjpAU1fjE6HxIQp /languages/csharp.min.js
sha384-FmsaZHRekzHoNL++5S8HZFIJNK42khOgzT3VRksnYVHAURRu3hL5xMgenu9lHyAr /languages/glsl.js
sha384-ubPsF/0wBxL7zEYtpuIL27F0zYtzIZknk+3GdMEcQw1v0Td6xAJ6gDhxHy0UFhk+ /languages/glsl.min.js
sha384-cZ2d3Mo/jmTF9r2kHWcHmA8hehxX8N44UN6LSkEhaCRe6t8e9ntd5JEuafywm0aw /languages/java.js
sha384-8mc5ynnm3AlnXn8P3ccSqVAaZIDoijPM08/Hp4DABy6GMy7EHCQFwiIUoGAaGJiO /languages/java.min.js
sha384-p/utwvqrRVOLlz0BjJ0BCGCb2liTDipfz47/QmGXz9hoPIjCKYEgmYUC30VmGgZy /languages/javascript.js
sha384-L/XmDiyusXomLRGcRmcBpPlboRFjpQNV747OJvg+sEOpgGYvUsNwcC4JLNQ2dI6O /languages/javascript.min.js
sha384-psmmPlbfEWGyvRapexDqkVTgNz7Y1xvlGdLNWQSafI4GFQYFDXPZxVXH1laU4n6l /languages/json.js
sha384-Bb6DhE3tUpBROwypL78TbhRUs9QbCt2GxcxVSYglt2l3MefrYkm4CfwjfWhRfQaX /languages/json.min.js
sha384-N16TmpAW2Qx3T6s3/C0f0jweUUSh69YsJ1+AnOsAePpjmmydXF/mjeY0MZEF/cPn /languages/lua.js
sha384-WES4Ky9nlehN2gBM6oY3/98hVtWF5PZnBO+7jK8ZVKFo+QR32zhfuRK+Mv9jQsOK /languages/lua.min.js
sha384-Z4QQuz3ChYj9P02v2CDc+Y0OAn3iWXtJnyNd0Q6QqW4GV28viT3zcS9tYSmb9x1L /languages/makefile.js
sha384-pYbMiHWycMKEfJaSEsquFRDTjCY7QHvQN0FIfDK0lVMd9DPJuOA7Kq5wZGecvYwM /languages/makefile.min.js
sha384-WNah6F2QDUbmrNCi0fSEyKJbSb01S1ijnoiwbDnegW7dm2Cz/H1CiH1HhWlUvj01 /languages/python.js
sha384-YDj7s2Wf0QEwarV3OB8lvoNJJCH032vOLMDo2HDrYiEpQ+QmKN+e++x3hElX5S+w /languages/python.min.js
sha384-rCXn7K5j/lD2PrSex2XCqyLKap2Ibnsls0uQCx4ZaezI1FJ5RYvoWcsAl/v8SKlE /languages/rust.js
sha384-VTNxHMz2AmpHxzSm8SvRI0As5+wID2j2XJBFtWTic2iEK8WbXgR1fymVQS9S2DvY /languages/rust.min.js
sha384-b1xMcp32tppp650j0U++x5VNyB+EUsx6P038Zo8qrrfGGzvwfAVoSMyZQnByUJeS /highlight.js
sha384-vZ2tdv2CHciSOEHVMm8WYJoe+tzIGYS9JUoQq6dMZCYOtd3/dcpllBp4C1+VhwNO /highlight.min.js
```

