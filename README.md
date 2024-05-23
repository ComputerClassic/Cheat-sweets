 cmd = right
    return (left, right, cmd)
def cheatsheet(lines):
    exps = [ parse(line) for line in lines ]
    exps.sort(key=lambda exp:exp[2])
    cheatsheet = {'_default': []}
