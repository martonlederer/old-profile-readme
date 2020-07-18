```ts
export class Info {

  name: string = 'Marton Lederer'
  age: number = 17
  nationality: string[] = ['Hungarian', 'Brazilian']
  languages: Record<string, string>[] = [{ 'Spanish': 'B2' }, { 'English': 'C1' }, { 'Hungarian': 'native' }]
  school: string = 'Alternatív Közgazdasági Gimnázium'
  occupation: string = 'Web Developer and Designer, Student'
  freetime: string[] = ['Gym', 'Reading', 'Hanging out with friends']
  musical_interest_years: number[] = [70, 80, 90]

}

export class Programming {

  languages: string[] = ['TypeScript', 'JavaScript', 'PHP']
  stylesheets: string[] = ['CSS', 'SASS', 'SCSS', 'Stylus']
  frameworks: string[] = ['Vue', 'Svelte', 'React']
  runtimes: string[] = ['Deno', 'Node']
  databases: string[] = ['MySQL', 'RethinkDB', 'Mongo']
  learning: string[] = ['Rust', 'Go', 'Angular']
  projects: string[] = ['Evolution X', 'nest.land', 'BetterAntispam', 'BloomAlts', 'Agrigo.farm/Cubilog']

}

export class Social {

  website: string = 'https://marton.lederer.hu'
  github: string = 'MartonDev'
  instagram: string = '@martonlederer'
  discord: string = 'Marton#6513'
  spotify: string = 'https://spoti.fi/2ZEq3CN'

}
```
