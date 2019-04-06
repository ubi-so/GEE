# GEE - Gestão de Estudantes de Erasmus. 
Projeto para a unidade curricular Sistemas Operativos


## Tabelas

Aluno(**idAluno**, nome, idUniDest, idUniOrig, idRespDest, idRespOrig)

Disciplina(**idDisciplina**, nome, ano, semestre, idRespDest, idUniDest)

Inscrito(**idAluno, idDisciplina**)

UniOrig(**idUniOrig**, nome)

UniDest(**idUniDest**, nome)

RespOrig(**idRespOrig**, nome, idUniOrig)

RespDest(**idRespDest**, nome, idUniDest)
