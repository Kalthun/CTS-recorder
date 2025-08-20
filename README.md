# CTS-recorder

## Steps

```
python -m venv env
```

```
env\Scripts\activate
```

```
pip install ...
```

```
nbstripout --install
```

## Output Structure

**NOTE**: Add Fall/NonFall dir after recordings

```
● outputs
┣ ● recordings
┃ ┣ ● 1
┃ ┃ ┣ 1-Fall-01
┃ ┃ ┣ 1-Fall-02
┃ ┃ ┣ 1-Fall-03
┃ ┃ ⋮
┃ ┃ ┗ 1-Fall-N
┃ ┣ ● 2
┃ ┃ ⋮
┃ ┃ ┗ 2-Fall-N
┃ ┣ ● 3
┃ ┃ ⋮
┃ ┃ ┗ 3-Fall-N
┃ ⋮
┃ ┗ ● N
┗ ● errors.txt
```
