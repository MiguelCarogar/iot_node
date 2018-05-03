# IoT-db

const setupDatabase = requite('IoT-db')

setupDatabase(config).then(db => {
const { Agent, Metric } = db
}).catch(err => console.error(err))