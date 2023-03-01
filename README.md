# svelte-cron-gen
Cron Generator Component for Svelte

Based on [mrbatista/angular-cron-gen](https://github.com/mrbatista/angular-cron-gen)

> Attention WIP!

## Instalation

```sh
#Should be:
npm i @cosminm/svelte-cron-gen
```


## Use

```html
<script>
  let myCron = '0 0/0 * 1/1 * ? *'
</script>

<SvelteCronGen
  value={myCron}
  language="en"
  showSeconds={true};
  showAdvanced={false};
  minutesStep={1}
/>
```

## Options

| Option | Value | Description |
| --- | --- | --- |
| value | (string) | Cron value |
| language | en (string) default | i18n - current languages: en, ro, es |
| showSeconds | true (boolean) default | Show seconds or not |
| showAdvanced | true (boolean) | Show advanced tab |
| minutesStep | 1 (number) | Minutes step |
