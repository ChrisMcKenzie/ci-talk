## Steps <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns" width="101px" height="120px" viewBox="10 -44 101 120" version="1.1"><defs/><g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage"><g id="Icons" sketch:type="MSArtboardGroup" transform="translate(-588.000000, -43.000000)" stroke="#222" stroke-width="2"><g id="Imported-Layers" sketch:type="MSLayerGroup" transform="translate(619.500000, 79.000000)"><path d="M22.828,12.265 L0.44,12.265 M13.44,20.193 L0.44,20.193 M19.44,28.123 L0.44,28.123" id="Stroke-1" sketch:type="MSShapeGroup"/><path d="M24.451,0.195 L38.451,20.479 L24.451,40.195" id="Stroke-2" stroke-linejoin="round" sketch:type="MSShapeGroup"/></g></g></g></svg>

```yaml
- npm-install
- npm-test
- go-setup-workspace
- go-install
- script:
    name: My Custom Script
    code: |
        echo "hello, world"
```

Note:
So Steps are another great feature of wercker and what they do is allow you
to define the steps required to test your software.

As you can here some of the more common steps are predefined and you just pop
them in and everything just works.

if you have a more complicated task or it just hasn't been defined in the
registry the simplist option you have is to compose a script step, these
let you write a bash script that will be executed on the container.
