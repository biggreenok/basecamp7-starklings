<a href="https://app.onlydust.xyz/projects/6196eca8-5467-4587-b9f7-8ebebab0f841">
<img src="https://img.shields.io/badge/OnlyDust-Starklings-grey?labelColor=000&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAATCAYAAACQjC21AAAAAXNSR0IArs4c6QAABNNJREFUOE9tlGtQ1FUchp/z/+8usLCArOAuICyggwpI4mVEQzNJVMQZb6WpqTikXSxDDC2bMUv9YAw2loWUOo06lo02XsoUL2NqogmmgmCgcleQ24Jclt09zeLo2OV8O7/3Pc+cOXPeV/A/S57B96Zm/Gu7m1MLsqYvOv+sZVNeXvwrg/rGhgcF7hEioP3fx8WzA7keDRGk1hst2cOiDl+rDR061qWf8S/y8lOMMvaB6ZFrv25SbWHGHhHm4+++Anz3CiGcTzhPgTJluJ6Yqzk9g3ULdmw+S3P38Bkflbv9JFv29nFszjyIqkg185fZwieqKZKSlcuSPLLfO2YEteNLaF0lxMBuF7QXKJGKLe7Vb3RT9y+5rsaT+vE+3BEJUTkN+VWJynf1FbY5slFHDH77FxeFLg7OPrvYy6Ms1//sBNTIfkB9NoSvEkLIXmABDfMiLNn7vBdtpuC3XBpPzyPY/c5XQ7pi3nTpppyu5G67Q2l+y/NI7wU+VU+idSQ6x29EjMxAKJXguJ8iNAlHxRykOg9b9XjjLpPfrDU0HNuEX+xO1OjCDtJGmMXAfOs/3lleNvHwSCXSqXV2GVCCl4NoAsftMtRLkWIy1hlz0B+covsZU8o6RNx18AfiIiAmy4Fu2twDB9RDHICJi1ihH0KW1mxXhEbB3gw6/xbACvZb0JyXLOKo+3Yp/VInKwUExXyO27pDMCwJwtfj7Img9bQHTefbnT11IOu9FH00SDt4J4BikPhOuA90QtdlKNuYI/y4dW06lthkVAa53WHQiZ1oEtKQzhAaT9nZOt+J46FGvkQX/d1rxSO/MKS7B442CFjaTkjGdugogQcXofKvQqFyuXYIZnMiZp5DYei0FgZse8SWWUY6CnUESBU/sI+iCV+KNXrtbdQBNZR3LCNidhq+0XmgOKG1B+ocdSKAgmob2qARBBGHgXDgLhIvNBgRBABeUDqAkr7eosjoYb6BR0Q+R5piMUUWMzr6KLi+dZtA1vSvEXOpunic+ngVHRb0rCKUOrrpRkcgGgyPgdvDKA/2Ua5N97TkU9vnASsLs/CWbqwJPoFJew8P0UhPc9gl8SOOrCo6069hxRcNw/DlJlaq6CKZIDwBPcwcQFmYQSnKMljOs7D6dbAF0wctI9FgwYkndhRElsi1yBf07ZwxNEm6nU7qsFGMlbt0MJUg/NEhwS+GunCj8ucfdabbpNfOJwQDRrQYhBONVNACboiE3qS8uLbn6pLdmrj6+61c0FVgUjWypsNLGHAjmX72eQitK57V4rT9Q62XKLeFk2TqlC9HHBbnSsZxpXEwlXTk/4rP6F7gpPSeMbMOq+dC73SrCW8PRDepoXVmSnGph9SNSiG4cyFC7/JViIvdY6WnLlg1n9+3tu9QNcjmveV9JxVtDkcnzufz8Ln0tG1yQ+Q7/SvZ6rDkiylZY2joDMzMXHA5PQqz+2qE7+PM322Pp6X+xvfRuzyrlQ2fbWuh4J6QNmzpv2Pa+rRtnmT1OPLdNpxbvMblapNWv1G1IcU64j5c+BrDQJcnjYqqXBqirVfiij/5oCbw2EnZY4PMMkKy/9OHTwY/ICPbsJ0KmfKFOTFtbeySmaVluwnrcukW7rqXtPsnZCwvPb5jj1Ltjm6ilaiyZ8vjb2wS2X7S7itMAAAAAElFTkSuQmCC" />
</a>

<a href="https://discord.gg/onlydust">
<img src="https://img.shields.io/badge/Discord-6666ff?logo=discord&logoColor=fff" />
</a>

<a href="https://twitter.com/intent/follow?screen_name=onlydust_xyz">
<img src="https://img.shields.io/twitter/follow/onlydust_xyz?label=Follow&style=social" />
</a>

<a href="https://t.me/+wu8frxmrbeliZWI1">
<img src="https://img.shields.io/static/v1?label=Telegram&message=Starklings Dev&color=eee&logo=telegram&style=social" />
</a>

# STARKLINGS

### An interactive tutorial to get you up and running with Cairo and Starknet

---

## Setup and run

Make sure you have Rust and Cargo installed with the `default` toolchain.  
With rustup `curl https://sh.rustup.rs -sSf | sh -s`

1. Clone the repo and go in the directory,  
   `git clone https://github.com/shramee/starklings-cairo1.git && cd starklings-cairo1`.
2. Run `cargo run --bin starklings`, this might take a while the first time.
3. You should see this intro message, run `cargo run --bin starklings watch` when you are ready!

## Start at a specific exercise `NEW`

To start watch at a specific exercise pass the name of the exercise to watch command.
For example, to start at `starknet1`,

```
cargo run --bin starklings watch starknet1
```

## Welcome message and instrucitons

```
starklings - An interactive tutorial to get started with Cairo and Starknet

       _             _    _ _
      | |           | |  | (_)
   ___| |_ __ _ _ __| | _| |_ _ __   __ _ ___
  / __| __/ _` | '__| |/ / | | '_ \ / _` / __|
  \__ \ || (_| | |  |   <| | | | | | (_| \__ \
  |___/\__\__,_|_|  |_|\_\_|_|_| |_|\__, |___/
                                     __/ |
                                    |___/

Thanks for installing starklings!

Is this your first time? Don't worry, starklings is made for beginners! We are
going to teach you a bunch of stuff about StarkNet and Cairo.

Here's how starklings works,

1. To start starklings run `cargo run --bin starklings watch`
2. It'll automatically start with the first exercise. Don't get confused by
error message popping up as soon as you run starklings! This is part of the
exercise that you're supposed to solve, so open the exercise file in an editor
and start your detective work!
3. If you're stuck on an exercise, there is a helpful hint you can view by
typing `hint` (in watch mode), or running `cargo run --bin starklings hint
exercise_name`.
4. When you have solved the exercise successfully, Remove `// I AM NOT DONE`
comment to move on to the next exercise.
5. If an exercise doesn't make sense to you, please open an issue on GitHub!
(https://github.com/shramee/starklings-cairo1/issues/new).

Got all that? Great! To get started, run `starklings watch` in order to get the
first exercise. Make sure to have your editor open!
```

## VSCode extension & language server

In order to have syntax highlighting and language server features, you will need to install the Cairo Language Server. The instructions available in the [Cairo repository](https://github.com/starkware-libs/cairo/tree/main/vscode-cairo)

## Inspiration

-   [Rustlings](https://github.com/rust-lang/rustlings), starklings is forked from Rustlings. Thanks to all the original [authors and contributors](https://github.com/rust-lang/rustlings)

## Testing

#### For Cairo related tests

```
cargo test cairo
```

#### For all tests

```
cargo test
```

## Contributing

Fork the Repository: Click on the "Fork" button on the repository's page. This will create a copy of the repository in your GitHub account.

Clone the Repository: Use  to clone the forked repository to your local machine.git clone <URL>

Create a Branch: Use  to create a new branch where you'll work on your changes. The branch name should be descriptive, such as including the issue number or a brief description of the changes you're making.git checkout -b <branch-name>

Make Changes: Add new exercises in the  directory and update information about the exercise in the  file or as per the specified instructions../exercises./info.toml

Commit Changes: After making changes, use  to stage the changes and then  to commit them to your local branch.git add .git commit -m "Descriptive message"

Push Changes: Push your branch with changes to your forked repository using .git push origin <branch-name>

Create Pull Request (PR): Visit your forked repository on GitHub. GitHub will usually provide a prompt to create a pull request from your branch. Select the base repository's  branch as the target for the pull request.dev

Describe Changes: In the pull request, provide a clear and concise description of the changes you've made. Reference any related issue numbers if applicable.

Submit PR: Once you've reviewed your changes and provided necessary information, submit the pull request.

Merge PR: The project maintainers will review your changes, suggest improvements if needed, and eventually merge your changes into the  branch after thorough testing.dev

Remember, it's essential to follow any specific contribution guidelines provided by the project. Additionally, keep communication open—engage with maintainers or contributors for guidance or assistance if required.

Always ensure your local repository stays updated with the upstream repository to avoid conflicts. Use  and  (if  is the name of the original repository) to keep your forked repository in sync.git fetch upstreamgit merge upstream/devupstream

Lastly, be patient during the review process; it might take some time for maintainers to go through and merge contributions.

