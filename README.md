
**1.** Install Pixi:

```bash
curl -fsSL https://pixi.sh/install.sh | sh
```

**2.** Open new terminal window.

**3.** Clone and install env:

```bash
git clone git@github.com:munch-group/mikkel.git
cd mikkel
pixi install
```

**4.** Copy segment data:

```bash
scp mheide@login.genome.au.dk:/faststorage/project/GenerationInterval/people/kmt/segments.parquet .
```

**5.** Open the `mikkel` *folder* in VScode.

**6.** Open the `mikkel.ipynb` notebook.

**8.** Click "Select kernel" at the top right and Choose this kernel `./pixi/envs/default/bin/python `.

**9.** Run the notebook cell by cell.
